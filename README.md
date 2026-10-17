<div align="center">

<img src="assets/hero-v2.svg" width="100%" alt="Vipin Bhardwaj — Computer Science student building full-stack, AI, and data projects"/>

<br/>

<a href="https://vipinbhardwaj-07.github.io/VipinBhardwaj-portfolio/">↗ Portfolio</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="https://algoverseweb.vercel.app">↗ AlgoVerse live</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/vipin-bhardwaj-55a5a93a9">↗ LinkedIn</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="mailto:vipinbhardwaj0827@gmail.com">↗ Say hello</a>

<a href="#profile">PROFILE</a>
&nbsp; · &nbsp;
<a href="#toolkit">TOOLKIT</a>
&nbsp; · &nbsp;
<a href="#how-i-build">HOW I BUILD</a>
&nbsp; · &nbsp;
<a href="#featured-work">FEATURED WORK</a>
&nbsp; · &nbsp;
<a href="#experience">EXPERIENCE</a>
&nbsp; · &nbsp;
<a href="#education-and-certifications">EDUCATION</a>

<br/><br/>

<img src="assets/metrics-v3.svg" width="100%" alt="Four projects, 1,000 synthetic sales records, nine visualizations, and two completed internships"/>

</div>

---

<a id="profile"></a>

## ✳ The short version

I'm **Vipin Bhardwaj**, a **Computer Science Engineering undergraduate at Sanskaram University (2024–2028)** with a growing project portfolio across software engineering, full-stack web development, data analytics, and applied machine learning.

I learn by building: planning a useful feature, implementing it, testing the result, and documenting what I learned. My current interests are **software engineering internships, full-stack development, AI/ML, and data-focused applications**. I’m strengthening my foundations in **data structures and algorithms, Python, Java, and modern web technologies**.

<details>
<summary><strong>Quick profile</strong></summary>

- **Degree:** Bachelor of Technology (B.Tech), Computer Science Engineering
- **University:** Sanskaram University
- **Expected graduation:** 2028
- **Experience:** Two completed virtual internships: Artificial Intelligence; Data Analytics with AI (six weeks)
- **Project areas:** Web applications, data analysis, machine learning, computer vision
- **Languages:** Python, Java, C, JavaScript

</details>

<a id="toolkit"></a>

## ⌘ My toolkit

<div align="center">
<img src="assets/toolkit.svg" width="100%" alt="Technical toolkit, grouped by programming languages, frontend, backend and databases, AI and data, developer tools, and current learning"/>
<br/><br/>
<img src="https://skillicons.dev/icons?i=python,java,c,js,html,css,react,vite,tailwind,nodejs,express,mongodb,mysql,tensorflow,opencv,git,github,vscode,postman&perline=10&theme=dark" alt="Python, Java, C, JavaScript, React, Node.js, MongoDB, TensorFlow, OpenCV, Git, and developer tools"/>
</div>

- **Programming languages:** Python, Java, C, JavaScript
- **Web development:** HTML5, CSS3, React, Vite, Tailwind CSS, Node.js, Express.js
- **Data and machine learning:** Pandas, NumPy, scikit-learn, TensorFlow, Keras, OpenCV, Matplotlib, Seaborn, Jupyter Notebook
- **Databases and tools:** MongoDB, MySQL, Git, GitHub, VS Code, Postman
- **Core concepts:** Data structures and algorithms, exploratory data analysis, data visualization, linear regression, K-means clustering, CNN-based image classification

<a id="how-i-build"></a>

## ⟳ How I build

I like making the path from a rough question to a shareable result visible: start with the problem, explore the data or user need, build a focused solution, check what it actually does, then document it.

<div align="center">
<img src="assets/build-loop.svg" width="100%" alt="An animated five-step project loop: notice a problem, explore and model, build, check the output, and share what was learned"/>
</div>

<a id="featured-work"></a>

## ✦ Selected projects

Projects below are selected to show a range of skills: building for learners, analyzing data, applying machine learning, and creating a polished web experience.

<div align="center">

<img src="assets/project-atlas.svg" width="100%" alt="Three project themes: an interactive DSA product, a supermarket data-analysis project, and an applied image-classification model"/>
<br/><br/>
<a href="https://github.com/VipinBhardwaj-07/AlgoVerse"><img src="assets/p-algoverse.svg" width="49%" alt="AlgoVerse — interactive data structures and algorithms learning platform"/></a>
<a href="https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis"><img src="assets/p-supermarket.svg" width="49%" alt="Supermarket Sales Analysis — end-to-end analytics and machine learning project"/></a>
<a href="https://github.com/VipinBhardwaj-07/CNN-Image-Classification"><img src="assets/p-cnn.svg" width="49%" alt="CNN image classification — cats versus dogs with TensorFlow and Keras"/></a>
<a href="https://github.com/VipinBhardwaj-07/VipinBhardwaj-portfolio"><img src="assets/p-portfolio.svg" width="49%" alt="Personal portfolio — component-based React application"/></a>

</div>

### 01 / [AlgoVerse — Interactive DSA Learning Platform](https://github.com/VipinBhardwaj-07/AlgoVerse) · [Live demo](https://algoverseweb.vercel.app)

An educational web platform for exploring data structures and algorithms through structured learning content, roadmaps, coding resources, and an AI learning assistant.

- Brought DSA learning modules, roadmaps, and resources together in a single interface.
- Built a responsive front end with interactive elements and a modern dark visual design.
- Published the learner-facing site on Vercel and configured a separate Node.js/Express service on Render.
- Implemented chat and health API routes; the study assistant can call Groq when configured, and the service applies request rate limiting.
- Added a Stripe Checkout-session endpoint to the backend.
- **Stack:** HTML5, CSS3, JavaScript, Vercel.
- **Backend:** Node.js, Express, Groq API, express-rate-limit, Render; Stripe Checkout integration.
- **Code deep dive:** [Chat API implementation](https://github.com/VipinBhardwaj-07/AlgoVerse/blob/main/ALGO%20VERSE/api/index.js) · [Render service configuration](https://github.com/VipinBhardwaj-07/AlgoVerse/blob/main/ALGO%20VERSE/render.yaml)

<details>
<summary><strong>Explore the AlgoVerse architecture</strong> · Vercel client → Express API → optional AI provider</summary>

<div align="center">
<img src="assets/algoverse-architecture.svg" width="100%" alt="AlgoVerse architecture: Vercel-hosted learning interface calls a rate-limited Node.js Express service on Render; chat can use Groq when configured, with a separate Stripe Checkout-session integration"/>
</div>

This is a project-level view of the services: the learning interface and API are deployed separately, and the chat provider is optional by configuration. Stripe Checkout is a separate backend integration.

</details>

### 02 / [Supermarket Sales Analysis](https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis)

An end-to-end analytics project that turns supermarket transaction data into visual analysis and machine-learning experiments. The reproducible dataset contains **1,000 synthetically generated transactions**.

- Cleaned and explored transaction, product, branch, customer, and time-based data.
- Created **nine visualizations** to communicate sales patterns and customer behavior.
- Applied **linear regression** for sales prediction and **K-means clustering** for customer segmentation.
- Packaged the work with an executed Jupyter notebook, reusable scripts, and a project report.
- The checked-in model output reports **R² = 0.891** and **mean absolute error = 54.43 sales units** for linear regression; the K-means output describes three spend segments.
- **Data limitation:** the 1,000 transactions are synthetically generated for a reproducible learning project; these metrics are not evidence of performance on real supermarket data.
- **Stack:** Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook.

<div align="center">
<img src="assets/lab-results.svg" width="100%" alt="Supermarket analysis outputs on a synthetic dataset: linear regression R-squared 0.891 and mean absolute error 54.43 sales units, plus three K-means customer segments with mean spend profiles"/>
</div>

<div align="center">
<a href="https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/blob/main/outputs/charts/08_actual_vs_predicted_sales.png"><img src="https://raw.githubusercontent.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/main/outputs/charts/08_actual_vs_predicted_sales.png" width="49%" alt="Actual versus predicted sales chart from the supermarket analysis"/></a>
<a href="https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/blob/main/outputs/charts/09_customer_segments.png"><img src="https://raw.githubusercontent.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/main/outputs/charts/09_customer_segments.png" width="49%" alt="K-means customer segmentation chart from the supermarket analysis"/></a>
</div>

<details>
<summary><strong>Open the analysis artifacts</strong></summary>

[Executed notebook](https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/blob/main/notebooks/Supermarket_Sales_Analysis.ipynb) · [Model metrics](https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/blob/main/outputs/model_metrics.txt) · [PDF report](https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis/blob/main/report/Supermarket_Sales_Analysis_Report.pdf)

</details>

### 03 / [CNN Image Classification — Cats vs. Dogs](https://github.com/VipinBhardwaj-07/CNN-Image-Classification)

A computer-vision project applying a **convolutional neural network (CNN)** to binary image classification.

- Implemented image preprocessing and CNN model training using TensorFlow/Keras.
- Added a prediction script for custom images and visualizations for accuracy and loss.
- The repository reports **90%+ training accuracy**; this is training performance, not a validation or test-set result.
- **Stack:** Python, TensorFlow, Keras, OpenCV, NumPy, Matplotlib.

### 04 / [Personal Portfolio](https://github.com/VipinBhardwaj-07/VipinBhardwaj-portfolio) · [Live site](https://vipinbhardwaj-07.github.io/VipinBhardwaj-portfolio/)

A responsive, component-based portfolio built to present projects, skills, and experience in a polished web experience.

- Organized the interface into reusable React components and centralized site content.
- Added Framer Motion animations and a rule-based FAQ assistant.
- Configured the application for deployment with GitHub Pages.
- **Stack:** React, JavaScript, Vite, Tailwind CSS, Framer Motion.

<a id="experience"></a>

## ◉ Experience

<div align="center">
<img src="assets/internships.svg" width="100%" alt="Two completed internships: Artificial Intelligence Virtual Internship with NASSCOM, IBM, and PBEL; and six-week Data Analytics with AI Internship with AICTE, BharatCares, and IBM SkillsBuild"/>
</div>

### Artificial Intelligence Virtual Internship
**NASSCOM · IBM · PBEL** | Completed

Completed a virtual internship focused on artificial intelligence.

### Data Analytics with AI Internship
**AICTE · BharatCares · IBM SkillsBuild** | Six weeks · Completed

Completed a six-week internship focused on data analytics with AI. Related project: [Supermarket Sales Analysis](https://github.com/VipinBhardwaj-07/Supermarket-Sales-Analysis).

<a id="education-and-certifications"></a>

## ⌂ Education and Certifications

**Bachelor of Technology (B.Tech), Computer Science Engineering** · Sanskaram University · **2024–2028**

**Additional certifications**

Python (GUVI) · Cloud Computing (Infosys) · YUVA AI (TCS iON) · PBEL (NASSCOM) · Generative AI (SJF) · Data Structures & Algorithms (Skill Up)

## ✉ Let’s connect

I’m interested in meeting engineers, students, and teams building useful software with web technologies, data, and AI.

<div align="center">

<a href="https://vipinbhardwaj-07.github.io/VipinBhardwaj-portfolio/">🌐 Portfolio</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/vipin-bhardwaj-55a5a93a9">💼 LinkedIn</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="mailto:vipinbhardwaj0827@gmail.com">✉ Email</a>

<a href="mailto:vipinbhardwaj0827@gmail.com"><img src="assets/footer.svg" width="100%" alt="Let's build something useful together"/></a>

</div>

<details>
<summary>GitHub activity</summary>

<div align="center">
<br/>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=VipinBhardwaj-07&theme=tokyo-night&hide_border=true&area=true&bg_color=0d1117" width="100%" alt="GitHub contribution activity"/>
</div>

</details>
