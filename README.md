# rollup-plugin-preserve-ts

> **JUST TESTING AN IDEA!**
>
> Want to kick it around with me? [Start a discussion!](https://github.com/karmaniverous/rollup-plugin-preserve-ts/discussions)
>
> Think I should build it? **STAR THE REPO!**

---

More and more often, I find myself sharing Typescript code with ChatGPT in order to kick around an idea.

Since I write modern, tree-shakable code, most of my projects have a LOT of source files, so this can be a real pain!

I use [Rollup](https://rollupjs.org) to build my projects, so I thought it would be cool to add a build output that consolidates all my Typescript into a single file without transpiling it to JS. Bit it turns out Rollup doesn't natively support that.

Opportunity knocks! 💡

The idea is to create a Rollup plugin that...

- Uses whatever other settings you are already using regarding entry points etc.
- Consolidates all of your TS files into a single, bundled file.
- Eliminates internal imports & consolidates external imports to the top of the file.

Here's [an exploration of the idea](https://chatgpt.com/share/6720731f-0850-800e-b303-f5fbef5c11c7) with ChatGPT o1-mini.

Should I build it? **STAR THE REPO** to vote YES!

---

Built with ❤️ on Bali! Find more great tools & templates on [my GitHub Profile](https://github.com/karmaniverous).
