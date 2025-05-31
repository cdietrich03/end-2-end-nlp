# end-2-end-nlp

## Requirements
1. Access this [link](https://huggingface.co/welcome) to create a Hugging Face account
2. Access this [link](https://huggingface.co/mistralai/Mistral-7B-v0.1) and enable your account to access the Mistral model or any other LLM that is preferred for use
3. Generate an access token through this [link](https://huggingface.co/settings/tokens). Be sure to copy it out, as you will not be able to see it after clicking out of the token.
4. Go to this [link](https://colab.research.google.com/) and create a Google Colab account.

## Running the code
1. While in this GitHub repository, navigate to the final_app.ipynb.
2. Once in this file, change the domain from github.com to githubtocolab.com.
3. This should open the file in a Google Colab notebook.
4. In Runtime > Change runtime type, ensure the runtime is set to T4 GPU
5. Uncomment the second code block to clone the repo into an environment. The code has been tested in Google Colab, so it is known to work there.
6. Ensure the config.yaml file contains the correct file paths for the data.
7. Run the Jupyter Notebook cell to download the requirements from the requirements.txt. (Will take 2-3 minutes)
8. Run the fourth Jupyter Notebook cell, and an interface and a link will pop up. Either one can be used to run the app.
9. Enter your generated Hugging Face token into the box when prompted to do so.
10. Click "Initialize RAG App" to load the system. (Note: This will take around 5 minutes.)
11. After the app has initialized, there will be a green check with a message that says "Initialization successful! You can now prompt the application."
12. Enter your student information in the query box and either click 'Submit' or hit the Enter key.
13. The answer will output in about 30-45 seconds.
14. If you want to change your query, enter a new set of information in the box.

## Examples generated from ChatGPT
1. Student Information:

11-year-old sixth grader with an autism spectrum disorder (ASD)

Processing speed is below grade level, but strong in visual-spatial tasks

Completed the O*Net Interest Profiler assessment

Shows strong interest in the “Realistic” and “Artistic” categories

Career interests: mechanical drafting, graphic design

Prefers hands-on, visual learning (e.g., drawing diagrams, using manipulatives) over lecture-based instruction

Receives speech therapy weekly for pragmatic language goals

Assessment Results:

O*Net Interest Profiler:

Highest scores in Realistic (“working with tools, machines, mechanical systems”) and Artistic (“creative expression, design”)

Lower scores in Social/Enterprising categories (prefers independent or small-group tasks)

Cognitive Testing:

Processing Speed Index: 80 (below average)

Perceptual Reasoning Index: 110 (above average)

Career Suggestions (based on interest profile):

Mechanical Drafter (creating technical drawings)

Graphic Designer (visual media; logo/layout design)

IEP-Related Notes:

Visual supports (graphic organizers, pictorial schedules) improve comprehension

Needs extra time on written tasks and tests (due to slower processing speed)

Benefit from occupational therapy for fine-motor skill support (e.g., printing, cutting)

2. Student Information:

17-year-old senior with a specific learning disability (SLD) in reading comprehension and written expression

Completed the O*Net Interest Profiler assessment

Shows strong interest in the “Investigative” and “Social” categories

Career interests: nursing assistant, laboratory technician

Prefers interactive, collaborative learning (group labs, discussions) and visual aids (diagrams, videos) over long passages of text

Uses text-to-speech software for reading assignments

Assessment Results:

O*Net Interest Profiler:

Highest scores in Investigative (“research, analysis, scientific inquiry”) and Social (“helping, teaching, counseling others”)

Lower scores in Realistic (hands-on mechanical tasks)

Academic Assessment (LD):

Reading Comprehension: 70 (well below grade level)

Written Expression: 75 (below grade level)

Math Reasoning: 95 (near average)

Career Suggestions (based on interest profile):

Certified Nursing Assistant (CNA): supportive patient care, teamwork in healthcare setting

Medical Laboratory Technician: sample analysis, data recording, problem solving

IEP-Related Notes:

Provide reading passages in audio format or with highlighted keywords

Use graphic organizers (e.g., concept maps) for comprehension and writing planning

Allow extended time on essays/tests; offer a scribe or speech-to-text for writing tasks

Incorporate hands-on lab activities and collaborative projects whenever possible

3. Student Information:

14-year-old ninth grader with attention-deficit/hyperactivity disorder (ADHD), predominantly inattentive presentation

Completed the O*Net Interest Profiler assessment

Shows strong interest in the “Enterprising” and “Conventional” categories

Career interests: retail management, administrative assistant

Prefers clear, structured tasks with step-by-step directions rather than open-ended assignments

Requires preferential seating (near teacher), frequent breaks, and checklists for task completion

Assessment Results:

O*Net Interest Profiler:

Highest scores in Enterprising (“leadership, persuasion, business operations”) and Conventional (“organizing, planning, managing data”)

Moderate score in Realistic (hands-on tasks)

Behavioral Assessment (ADHD):

Inattention Scale: 90th percentile

Hyperactivity/Impulsivity Scale: 60th percentile

Career Suggestions (based on interest profile):

Retail Manager: overseeing store operations, motivating staff, customer engagement

Administrative Assistant: scheduling, record keeping, office organization

IEP-Related Notes:

Provide written and verbal task instructions; use checklists to track steps

Allow short, timed breaks (e.g., 3–5 minutes) after 15–20 minutes of work

Offer a structured daily planner/calendar for assignment deadlines

Minimize distractions: preferential seating, noise-cancelling headphones for independent work


