---
description: >-
  More questions will be added here by our Mod team as we get them. If you have
  a question that's not here, tell one of our team!
---

# 🤔 FAQ

<details>

<summary>Can I use DevGPT for work / in my development team?</summary>

Use of DevGPT isn’t limited to personal only, we’ve developed this with enterprises in mind, and our 3rd party database provider is SOC2 compliant. We do not store any of the data used during the generation of your code.

If you want to use it in a larger tech team, we do offer an enterprise solution with added benefits, send an email to support@devgpt.com with your message if you would like more information.

</details>

<details>

<summary>I'm getting the error "Microsoft Defender SmartScreen prevented an unrecognised app from starting"</summary>

This error is caused by the app being unsigned on Windows, and is still an active error.

We have a fix in progress for it. The app is already signed on Mac, but we're awaiting the process to finish for Windows to have this issue resolved.

In the meantime, you are able to pass / skip this error, but only do that if you feel comfortable doing so. This doesn't affect or change the in-app function of DevGPT in any way.

\
Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>How do I upgrade my DevGPT plan?</summary>

You can upgrade your plan directly in the app of DevGPT, which will direct you to Stripe that will handle the payment.

Do not upgrade your account using any other method but this.

Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>Why is my download taking so long?</summary>

We are working on reducing our bundler size to reduce download time, but in the meantime our download size and time is quite long. We will reduce this.

This is not helped by the fact we do not have a loading screen, but as long as you're running the latest version, you should have no issue loading the app / the app should always run, eventually. On average it will be under or around 20 seconds.

If your download / load is taking far longer than this (10m+): Check your internet connection, check you have enough space available on your device. If this doesn't help, you may want to get additional help via our team in Discord.

Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>I am getting the error: "Oops, something went wrong! Error 0008"</summary>

This error is often caused by being on the incorrect version. In version 1.1.1 we made it so people didn't have to immediately upgrade after a new version is released. However, if you are in a version earlier than 1.1.1, you will have to upgrade versions. It is always recommended to be on the newest version for the best experience. You can get new versions of the app here: [https://www.devgpt.com/download](https://www.devgpt.com/download)



Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>I upgraded my account but it's not reflecting in the app</summary>

If you have upgraded but on the sidebar in the app you still have an 'Upgrade' button, your app is not reflecting the upgrade correctly. The app will instantly update on upgrade, but here are some steps you can follow / things you can check if this isn't happening.

* Make sure you have a subscription to DevGPT. You can only upgrade via the app, you can't upgrade via the web or any other means. We have found some users have accidentally purchased WebKit (another company that sometimes uses the name DevGPT). This is not us.
* You mistyped your email at some point and have signed up again with a different one, or are using a different one. The email that you put into the Stripe payment will not matter: only the email that your account is using. Do make sure that all of your emails are correct, and spelt correctly.
* Try refreshing the app
* Try to sign in, and sign out

I'll keep updating this post as we get more reasons for this happening. If this hasn't fixed your issue and you have checked the above: please get directly in touch with one of our team and they will help you. I (tom @ devgpt) will happily help you fix these issues.



Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>How do I reset my password?</summary>

In the app during sign in, we have a reset password function. This will open, you enter your email, that will send you a magic link that signs you in to our site

Here, you can reset your password and access additional support docs.



Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>I have a new idea / want to report an issue</summary>

You can do this at devgpt-releases github issues [https://github.com/february-labs/devgpt-releases/issues](https://github.com/february-labs/devgpt-releases/issues). It doesn't have to be an "issue" for you to report it here, it can be a suggestion, idea, or any feedback at all! :)



Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>Why are my prompts are freezing, not running, crashing, not working?</summary>

As of the version 1.1.1, you should now be able to receive a brief error message of why your prompt didn't work. However, these messages are often targeted to our Dev team, instead of being useful for you. I've compiled a list of reasons that I've found user's prompts are sometimes failing. Issues:

* You may be on a previous version of DevGPT. Downloads: [https://www.devgpt.com/](https://www.devgpt.com/)
* Your prompt may be too long (400+ characters)
* Your context may be too long (150+ characters)
* Your answers to the follow-up questions are too long (100+ characters)
* Your repo is empty (this will be fixed in a future update)
* Your prompt is asking a question. (e.g How does this work?)
* Your prompt was providing code directly in the prompt (e.g Fix this code: const a + b)

Suggestions:

* Rewrite your prompt to the following style (In X file, do this thing)
* Download the newest version
* Test on multiple repos instead of the same repo
* Simplify your tech stack and context

Example perfect prompts:

* In \<file\_name>, make the "Example" button say "Something else". onClick the button should become disabled, change the text to 'Different text', and on response from the API change it back to 'Something else'
* Write a unit test for \<file\_name>
* Refactor \<file\_name> to make it easier for junior devs to understand and improve any syntax
* Write unit tests for \<name\_of\_a\_folder\_containing\_not\_too\_many\_files>
* Create a new component called MyExample.jsx that stores a list of something and maps it to a list of something else

I'll add more fixes, example prompts and issues to this list as they are coming in.



Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>Why does my DevGPT take so long to install / download / load?</summary>

This is something we have noticed in loading, and are working on reducing our package size to reduce overall download size and loading time.

In the meantime we do apologise for the slightly longer than usual load time. If you are waiting anywhere over 7-10 minutes however, you may want to consider a reload, or to look for more help in the DevGPT discord.



Written by Tom @ DevGPT (16/09/2023)

</details>

<details>

<summary>What is the file limit of repos that can be used with DevGPT?</summary>

There is no file limit, you are allowed to process any repo of any size.

In our experience however repos over 80k files may begin to struggle with generation. If you are unsure, talk to our team in Discord! We may be able to help you personally.

</details>

<details>

<summary>How do I cancel my plan / subscription?</summary>

If you'd like to cancel your DevGPT plan, you can do this via your receipt that was sent to you when you subscribed. If you don't have this, or are unable to do this, you can send your email along with the request to cancel to support@devgpt.com, and your refund will be processed.

</details>

<details>

<summary>How do I exclude files / stop DevGPT from reading my node_modules</summary>

We have now removed the functionality of users having to manually enter the files that they would like to be removed from the generation. This is now entirely handled by us, and default / baggage files will not be used in the generation.

</details>

<details>

<summary>Is ____ supported? (Flutter, Dart, Next, Python, Go, Rust, Svelte...)</summary>

Our prompts are ran through gpt-4-32k, meaning anything that you are used to running in other AI's including ChatGPT will have a similar outcome here. In our benchmarking we've found success most languages, but we always recommend: Test on the free version, this will tell you how much of a grasp it may have in the paid version.

</details>
