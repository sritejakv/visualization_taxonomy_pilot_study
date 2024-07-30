# Artifact for the pilot study

This artifact contains the interview transcripts and the concept boards of the six interview participants of the initial pilot study conducted as part of the paper *Visualization Task Taxonomy to Understand the Fuzzing Internals (Registered Report), FUZZING ’24, Vienna, Austria.*

## Folder structure

- initial_question_catalogue.pdf: It contains the initial questions used in the study. These questions are asked by the interviewer to all the participants to keep the study discussions focused on understanding internals of fuzzing using visualization analysis.

- InterviewData:
This folder contains interview data of the six participants. There is a folder for each participant: P1, P2, P3, P4, P5, P6.
Each of the folder contain two files
    - Px.png: An image of the concept board for the second and third part of the study filled during the interview
    - Px_transcript.pdf: Anonymized transcript of the participant for the second and third part of the study. Each transcript is also annotated with the analysis tasks mentioned during the interivew along with the corresponding explanations.

- QualitativeDataAnalysis:
The spread sheet, "coding_of_visualization_analysis_tasks.xlsx" contains complete details of the coding protocol for the visulization analysis tasks. The spread sheet contains four sheets:
    - Codes: explain the task specification (Table 1 in the paper)
    - Discussion & Conflicts: contains the coded data from two coders (Coder1 and Coder2) for each of the visualization analysis tasks along with the participant information. 
        - Column A contains the coder information, Coder1 or Coder2
        - Column B contains the participant ID (Table 2 in the paper)
        - Column C contains the internal analysis task ID that can be mapped to the visualization analysis tasks in the interview transcripts.
        - Columns D - G contains the four parts of task specification for each visualization analysis task from both coders next to each other to faciliate comparison and identify conflicts
        - Column H contains notes along with duplicate and subset information
        - Column I mentions the conflict ID in case there is a conflict between the codes and Column J mentions the conflict resolution
    - Final Codes: contains the final 54 task specifications extracted after discussions between the coders and application of duplicate and subset operators (Section 3.3 in the paper).
        - Column A contains the participant ID (Table 2 in the paper)
        - Column B contains the Task ID according to the paper (Table 4 and Table 5)
        - Column C contains the internal analysis task ID that can be mapped to the visualization analysis tasks in the interview transcripts.
        - Columns D - G contains the four parts of agreed task specification for each of the 54 visualization analysis tasks
        - Column H contains the internal analysis task IDs of the duplicates
        - Column I contains the internal analysis task IDs of the subset relationships
        - Column J contains notes
    - Discarded codes: contains the discarded task specifications along with the participant information.
        - Column A contains the participant ID (Table 2 in the paper)
        - Column B contains the internal analysis task ID that can be mapped to the visualization analysis tasks in the interview transcripts.
        - Columns C - F contains the four parts of task specification for each discarded visualization analysis task
        - Column G contains the internal analysis task IDs of the duplicates
        - Column H contains the internal analysis task IDs of the subset relationships
        - Column I contains notes