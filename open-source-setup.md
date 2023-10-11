---
description: >-
  Thank you for decided to contribute towards DevGPT and making it the best code
  agent for software development! Here we will outline the steps required to get
  DevGPT running locally.
---

# 💻 Open Source Setup

### Getting Started

1. Clone our Open-Source repository [here](https://github.com/february-labs/devgpt-releases).
2. You'll need to set-up a Supabase Project to run DevGPT locally - This is outlined between 0:00 - 0:35 [here](https://www.youtube.com/watch?v=6fFHgHqSbt8).
3.  Once you've created your Supabase Project, you'll need to get the Project URL and Anon Public key to connect your DevGPT repository to Supabase; both of these can be found within your API settings: `https://supabase.com/dashboard/project/{PROJECT_ID}/settings/api`. Once you've got these, copy and paste both keys into your `EXAMPLE.env` file inside of your repository:&#x20;

    ```
    NEXT_PUBLIC_SUPABASE_URL={SUPABASE_URL}
    NEXT_PUBLIC_SUPABASE_ANON_KEY={SUPABASE_ANON_KEY}
    ```
4. After adding your keys, you'll need to go to the SQL Editor, which can be found at: `https://supabase.com/dashboard/project/{PROJECT_ID}/sql/new`. Once you've opened your editor, you'll need to copy and run the schema.sql file's contents, which can be found in your repository `supabase/schema.sql`.
5.  After connecting your Supabase account, you'll need to add your OpenAI API key to the `EXAMPLE.env`. Information where to find this can be found [here](https://help.openai.com/en/articles/4936850-where-do-i-find-my-secret-api-key).&#x20;

    ```
    NEXT_PUBLIC_OPENAI_API_KEY={OPENAI_API_KEY}
    ```
6.  Install dependencies and run your local development environment by running these commands:

    ```bash
    npm install || yarn install
    =================================
    npm run dev || yarn run dev
    ```
7. With DevGPT running locally, you'll be able to sign up and see the new account in your Supabase instance; you may need to confirm your email address and log back into your local DevGPT environment to activate your account, and then you'll be ready to go!

Happy Coding! We can't wait to see what you can do with DevGPT - We'd love to hear about your adventures or any questions you have on our [Discord.](https://discord.gg/6GFtwzuvtw)
