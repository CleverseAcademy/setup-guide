# Node.js setup guide

Node.js is a JavaScript runtime, used in our courses
to run the React framework and the back-end code itself.

Most of our dependencies (like NPM and the linters) will
depend on it, so you will absolutely need to install Node.

## NPM and cousins

NPM and its cousins (Yarn and PNPM) are package managers
for JavaScript/TypeScript development.

Unlike the system package manager like `brew` or `winget`
that we use to install system software like the editor
and Node, these development package managers are used
to install development software packages like libraries
(i.e. code that other people wrote and published) to our
projects.

NPM is the standard, although PNPM is increasingly getting
popular due to reduced disk footprint.

## Node.js and TypeScript

The TypeScript compiler `tsc` runs on Node, and it compiles
TypeScript code downs to JavaScript program that we will
actually run with Node.

To write a Node app in TypeScript, you will need `@types/node`
to make TypeScript compiler understands Node TypeScript symbols.
