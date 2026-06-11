[comment]: # "You may find the following markdown cheat sheet useful: https://www.markdownguide.org/cheat-sheet/. You may also consider using an online Markdown editor such as StackEdit."

## Project title: DataScrim

### Student name: Aswin Sajan

### Student email: as1810@student.le.ac.uk

### Project description:

The aim of the project is to built a fullstack webapp which help secondary school teachers to deliver mathematics lessons through esports data analysis. The webapp fetches the data from google drive using google's api and displays it as chart types, axes and color schemes without displaying the raw data to the end user. A dynamic quiz generating system using a free LLM model produces context-aware mathematical question based on maths topic, chart type and difficulty level. The teacher dashboard consists of session preperation and live management, and a frictionless student login via a session code. Support for 30+ participants users for realtime engagement tracking.The platform is designed for scalability and pedagogical effectiveness.

### List of requirements (objectives):

[comment]: # "You can add as many additional bullet points as necessary by adding an additional hyphon symbol '-' at the end of each list"

Technologies used

- Next.Js - handles UI, routing and API endpoints.
- Vercel - Cloud deployment.
- Python FastAPI - handles Google Drive fetching and LLM quiz generation.
- LLM free APIs provided by Nvidia / Openrouter
- Railway/PythonAnywhere - deployment for python microservices.
- Supabase - Postgres db, Google Oauth , realtime subscriptions.

Essential:

- Fetching esports dataset from Google Drive using API without exposing raw data.
- Visualisation builder for teachers.
  -Role-based Interfaces - Teacher dashboard and student interface.
- Quiz generation (using LLMs).
- Support for 30+ cocurrent student users.
- Authentication for teachers.

Desirable:

- Teachers can view and edit AI genrated questions before presenting.
- Configure difficulty levels.
- Session history - allows teachers to use previously used dataset and quiz sets.
- Question type selectors like read the chart , compare values , calculate from given data ,true/false etc.

Optional:

- Websocket-based real-time push updates replacing Supabase. (Supabase integration is a all in one package )
- Export functionality allowing teachers to download session summaries in PDFs and CSVs.
- Student authentication system.
- Click the charts data point as answers intead of multiple choice answers.

## Information about this repository

This is the repository that you are going to use **individually** for developing your project. Please use the resources provided in the module to learn about **plagiarism** and how plagiarism awareness can foster your learning.

Regarding the use of this repository, once a feature (or part of it) is developed and **working** or parts of your system are integrated and **working**, define a commit and push it to the remote repository. You may find yourself making a commit after a productive hour of work (or even after 20 minutes!), for example. Choose commit message wisely and be concise.

Please choose the structure of the contents of this repository that suits the needs of your project but do indicate in this file where the main software artefacts are located.
