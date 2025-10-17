In-class activity for Wednesday, October 15, 2025

Follow these steps exactly:

1. Make a copy of the following workshop files and folders into your workspace (or a location of your choice):
   - DataStreamVisualization_Workshop
   - LinearRegressionArchitecture_Workshop
   - PerformanceMetricsClassification
   - KNearestNeighbors_Workshop
   - LogisticRegressionClassifier

2. Make a copy of the study guide on the course shell and save the guide as a file called "StudyGuide.txt"

3. ZIP all the workshop IPYNB files into a file called "StudyMaterials.zip"

4. Open a new LLM session.

5. Upload "StudyGuide.txt" and "StudyMaterials.zip" to the session.

6. Use the following prompt in the LLM session (do NOT start the quiz yet; tell the LLM to "stand by" and wait for your command):

--- BEGIN PROMPT ---

You are interviewing me for an ML Specialist Position. Follow these instructions exactly and stand by (do NOT start the quiz yet) until I tell you to begin.

Background about me (to include in your interview context):
- I am a Data Scientist and Machine Learning Engineer, fresh out of college.

Background about you (to include in your interview context):
- You are a seasoned Data Scientist, Machine Learning Engineer, and interviewer.

Task for you (the LLM interviewer):
1. I will upload two files: "StudyGuide.txt" and "StudyMaterials.zip". Unzip the workshops included in "StudyMaterials.zip", read and understand the notebooks and materials inside them, and read the study guide in "StudyGuide.txt".

2. Produce the following outputs:
   a. A 500-word summary of the learning content across the unzipped workshops. Focus on key concepts, algorithms, practical exercises, and takeaways relevant to ML engineering and data science.
   b. A 100-word summary of the topics in the study guide, tailored for a job interview preparation.
   c. A table that matches the study guide topics to the materials in the workshops, indicating for each topic whether the materials cover it fully, partially, or not at all. Include a brief note for any gaps.
   d. A 15-question multiple-choice quiz (MCQ). Each question should have five answer options labeled A, B, C, D, and E. The quiz should be based on the combined knowledge requirements implied by the study guide and the workshop materials.
      - The LLM should start the quiz in interactive mode, asking one question at a time and waiting for my answer before proceeding to the next question.
      - After I finish all questions, provide a score and detailed feedback on incorrect answers.
      - Based on the questions I got wrong, generate a new Jupyter Notebook called "JobInterviewGuide_Workshop.ipynb" inside a folder named "JobInterviewGuide_Workshop". The notebook should include:
         * A short intro markdown explaining the purpose and how the notebook was generated.
         * For each concept I answered incorrectly, include an explanatory markdown cell covering the concept, and at least one Python code cell with scaffolding (datasets, code templates, or exercises) to practice that concept. Use the workshop notebooks as example style and structure.
         * Clear instructions on how to run the cells and what to expect.
   e. Include in the notebook any additional resources or readings that would help me fill the identified gaps.

3. When creating the "JobInterviewGuide_Workshop.ipynb", follow the structure and style of the existing workshop notebooks. Use markdown explanations and runnable Python cells where appropriate.

4. Finally, wait for my command to begin the interactive quiz. Do not start the quiz until I explicitly say "Start Quiz".

--- END PROMPT ---

7. Push the generated "JobInterviewGuide_Workshop.ipynb" to GitHub in a repository or branch you control. Include a markdown file in the repo that contains the entire LLM session transcript and all prompts you issued, including the prompt above.

Notes and deliverables:
- Deliver the following files in your workspace or repository:
  - StudyGuide.txt (copied from the course shell)
  - StudyMaterials.zip (containing the workshop notebooks)
  - JobInterviewGuide_Workshop/JobInterviewGuide_Workshop.ipynb (generated after the quiz)
  - A markdown file containing the full LLM session transcript and prompts used.

Verification checklist:
- The README instructs the LLM to stand by and not start the quiz until the user issues the "Start Quiz" command.
- The JobInterviewGuide_Workshop notebook is only generated after the quiz and tailored to wrong answers.

End of in-class activity instructions.
