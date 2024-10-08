<h1>CourseCraft.ai
</h1>
<h2> A custom learning platform powered by AI</h2>

<h3>Skills used: </h3>
<ul>
    <li>Gemini AI</li>
    <li>Next.JS</li>
    <li>Drizzle ORM</li>
    <li>Postgre SQL</li>
    <li>Clerk</li>
    <li>Tailwind CSS</li>
    <li>ShadCN UI</li>
    <li>Youtube API</li>
</ul>

<h2>Key features of this application: </h2>
<ul>
    <li>Created using Gemini AI to generate complete courses based on categories, duration, number of chapters, levels etc.</li>
    <li>Users can buy and view other courses, promt with topic detail providing an interactive learning experience.</Li>
    <li>Integrated Youtube API to generate video tutorials for each chapter and notes with edit functionality.</Li>
    <li>Clerk authentication through email or with upto 2 social accounts.</Li>
</ul>

<h3>Steps to run this project in your device: </h3>
<p>Create an empty directory and run the following commands in the terminal: </p>

```bash
    git clone https://github.com/GarimaUttam/CourseCraft.ai.git

    cd CourseCraft.ai

    npm i
```

<p>Also, create a .env file in the root directory of the project and your environment variables. <br/> The following variables must be added: </p>

```bash
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY =
    CLERK_SECRET_KEY =

    NEXT_PUBLIC_CLERK_SIGN_IN_URL =
    NEXT_PUBLIC_CLERK_SIGN_UP_URL =
    
    NEXT_PUBLIC_DRIZZLE_DB_URL = 

    NEXT_PUBLIC_GEMINI_API_KEY = 

```

<p>Finally to run this project, enter the following command: </p>

```bash
    npm run dev
```


<p>Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.<br/><br/>You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.<br/></br>This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
</p>

![image](https://github.com/user-attachments/assets/309926c8-4f04-430f-b0a5-fee28fdc9c64)
