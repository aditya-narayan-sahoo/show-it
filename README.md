<div align="center">
  <br />
    <a href="https://youtu.be/Zq5fmkH0T78?feature=shared" target="_blank">
      <img src="https://github.com/user-attachments/assets/c89ef10d-9230-4b17-ba06-960f90c77150">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=react&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Sanity-black?style=for-the-badge&logoColor=white&logo=sanity&color=F03E2F" alt="sanity" />

  </div>

<h3 align="center">Apps Directory Platform</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🔗 [Screenshots](#images)
5. 🤸 [SetUp](#setup)

## <a name="introduction">🤖 Introduction</a>

A Next.js 15 platform where users can submit their startup ideas for virtual pitch competitions, browse other
pitches, and gain exposure through a clean minimalistic design for a smooth user experience.

## <a name="tech-stack">⚙️ Tech Stack</a>

- React 19
- Next.js 15
- Sanity
- TailwindCSS
- ShadCN
- TypeScript

## <a name="features">🔋 Features</a>

👉 **Live Content API**: Displays the latest startup ideas dynamically on the homepage using Sanity's Content API.

👉 **GitHub Authentication**: Allows users to log in easily using their GitHub account.

👉 **Pitch Submission**: Users can submit startup ideas, including title, description, category, and multimedia links (
image or video).

👉 **View Pitches**: Browse through submitted ideas with filtering options by category.

👉 **Pitch Details Page**: Click on any pitch to view its details, with multimedia and description displayed.

👉 **Profile Page**: Users can view the list of pitches they've submitted.

👉 **Editor Picks**: Admins can highlight top startup ideas using the "Editor Picks" feature managed via Sanity Studio.

👉 **Views Counter**: Tracks the number of views for each pitch instead of an upvote system.

👉 **Search**: Search functionality to load and view pitches efficiently.

👉 **Minimalistic Design**: Fresh and simple UI with only the essential pages for ease of use and a clean aesthetic.

  and many more, including the latest **React 19**, **Next.js 15** and **Sanity** features alongside code architecture and
  reusability

## <a name="images">🔗 Screenshots</a>
![{1365F862-9DE0-4108-AEB2-358214558D16}](https://github.com/user-attachments/assets/fe3bf106-39c3-4fea-8516-d7e7762879c8)
![{3A16B07F-B5F7-4F27-B0E5-638E68F69EC6}](https://github.com/user-attachments/assets/897605a4-6c69-49cf-b9a7-9e9f196c7d77)
![{001415E4-A259-4F92-A39B-DC1D24C703C0}](https://github.com/user-attachments/assets/7bcc695a-7045-4e92-a904-46c48e5f7507)
![{467953A5-087E-473B-A858-8AF34C59C2BB}](https://github.com/user-attachments/assets/58f73b55-5946-420c-9740-c3f04e136be8)
![{9406E441-1396-4153-A84D-0D921BAD8EED}](https://github.com/user-attachments/assets/cddc106e-1759-436d-a7e3-de3ed1c219e3)
![{6C0E5F25-5777-4269-82F1-AEEFDB17C251}](https://github.com/user-attachments/assets/025805e8-2198-40f1-8d67-8986a92c6356)


## <a name="setup">🤸 Setup</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/aditya-narayan-sahoo/show-it.git
cd show-it
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_SANITY_PROJECT_ID=
NEXT_PUBLIC_SANITY_DATASET=
NEXT_PUBLIC_SANITY_API_VERSION='vX'
SANITY_TOKEN=

AUTH_SECRET= 
AUTH_GITHUB_ID=
AUTH_GITHUB_SECRET=
```

Replace the placeholder values with your actual Sanity credentials. You can obtain these credentials by signing up &
creating a new project on the [Sanity website](https://www.sanity.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.


### Citation

- This project was made with the help of this video [YouTube Video](https://www.youtube.com/watch?v=Zq5fmkH0T78)
- You can check out his tutorials here : [https://www.youtube.com/@javascriptmastery/videos](https://www.youtube.com/@javascriptmastery/videos)
