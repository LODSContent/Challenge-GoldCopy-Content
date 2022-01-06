# The requirement title goes here

<span class="guidance">
[Requirement Title Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Task%20Title.png "Tips for writing engaging requirement titles")
</span>

Optionally, you can define the requirement scenario here.

- Each requirement will have at least one task that a learner must perform in order to complete the requirement. You want to tell them what to do but not how to do it.

<span class="guidance">
 [Task Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Instructions.png "Writing great tasks")
</span>

```-linenums

If there is code the learner needs to reference, put it in a "code fence".
Use ` ` ` and ` ` ` (without the spaces) to set the code fence that defines the code block.
Multiple lines of code placed in a code fence will show up as a block.
Define code that contains quotation marks. 
Code that contains quotation marks should be placed in a fenced code block or should use the Copy to clipboard or Type Text features.
```

<span class="guidance">
[Code Block Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Code.png "How to use code blocks")
</span>

## To create the following table, use this syntax:

```
   | Element | Reason |
   |:--|:--|
   | Properties | When you want a learner to configure settings or properties, consider using a table. 
   | Tables | Tables allow you to display a lot of relevant information in once place without the need to write an instructional step for each setting. 
   | Settings |Use tables to display configuration settings. 
```

   | Element | Reason |
   |:--|:--|
   | Properties | When you want a learner to configure settings or properties, consider using a table. 
   | Tables | Tables allow you to display a lot of relevant information in once place without the need to write an instructional step for each setting. 
   | Settings |Use tables to display configuration settings. 

<span class="guidance">
 [Table Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Table.png "Proper use of tables in challenges")
</span>

## To create the following hint, use this syntax:
```
><details class="hint-icon">
><summary title="Select to Expand">Expand this hint for guidance on creating hints</summary>
>    - Give the learner guidance on the next task.
>    - Each hint should describe one instructional step. 
>    - Learners should be able to expand a hint for one step without seeing any other hints for the task.
>    - The hint tells the "how" of the task.
>    - Use an expandable hint to provide learners with the details of how to perform the action in >the step. 
>   
></details>

```

   <details class="hint-icon">
   <summary title="Select to Expand">Expand this hint for guidance on creating hints</summary>
   - Give the learner guidance on the next task.
   - Each hint should describe one instructional step. 
   - Learners should be able to expand a hint for one step without seeing any other hints for the task.
   - The hint tells the "how" of the task.
   - Use an expandable hint to provide learners with the details of how to perform the action in >the step. 
   
   </details>

<span class="guidance">
[Hint Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Hint.png "How to write hints")
</span>

## To create the following knowledge block, use this syntax:
```

   <span class="know-icon">Add knowledge blocks to provide additional context. This often includes links to [source material]https://skillable.com) on the topic.</span>

```

   <span class="know-icon">Add knowledge blocks to provide additional context. This often includes links to [source material]https://skillable.com) on the topic.</span>

<span class="guidance">
[Knowledge Block Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Knowledge%20Block.png "Proper use of knowledge blocks")
</span>

## To create the following note, use this syntax:
```

   <span class="info-icon">Use notes to make it easier for learners to perform a task. You can use a note to provide an alternative method of performing a task. This is used to help explain the "why" of a task, or to point out specific information related to a task</span>

```

   <span class="info-icon">Use notes to make it easier for learners to perform a task. You can use a note to provide an alternative method of performing a task. This is used to help explain the "why" of a task, or to point out specific information related to a task</span>

<span class="guidance">
  [Note Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Tip.png "Adding notes to challenge labs")
</span>


## To create the following alert, use this syntax:
```

   <span class="warn-icon">Use alerts to notify learners of something critical to completing the lab. This could be anything from specific settings that need have specific values to error messages the learner might see and what to do about them.</span>

```

   <span class="warn-icon">Use alerts to notify learners of something critical to completing the lab. This could be anything from specific settings that need have specific values to error messages the learner might see and what to do about them.</span>

<span class="guidance">
  [Alert Guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Alert.png "Adding notes to challenge labs")
</span>



- Add multiple tasks for every requirement.

>   <details class="hint-icon">
>   <summary title="Select to Expand">Expand this hint for guidance on ...</summary>
>   Give the learner guidance on the next task.
> 
>   </details>

   <span class="know-icon">Add knowledge here.</span>

   <span class="info-icon">Add information here.</span>
>

!INSTRUCTIONS[](https://raw.githubusercontent.com/LODSContent/Challenge-V2-Framework/master/Templates/LevelSpecific/Checks/@lab.Variable(difficulty).md)

<span class="guidance">
[Check your Work guidance](https://lodmanuals.blob.core.windows.net/lms/CLabsInstTemplate/Check%20Your%20Work.png "How to help learners validate their work with Check Your Work entries")
</span>
 @lab.Activity(SimpleScript) 

 @lab.Activity(ScoringFramework)

 ===
