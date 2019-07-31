# Questions

1\.  What is hot-reloading?

```
It is a state of an app used during devs that allows the app to
refresh as soon as changes have been saved to the code.
```

2\.  Why did you need you to set up a server for your production build but not when running your app in development?

```
I honestly have doubts why, and I will ask for clarification about.
But if I have to take a guess it is because once I deploy my app I
want my users to have a static server running on their devices that will maintain the actual state/environment of their experience. IMHO.
```

3\. After you ran `yarn eject`, you should have seen two new directories created, `config` and `scripts`. Choose 3 files from these directories and describe what they do. You aren't expected to understand everything that's going on in these files, but do make sure you understand in general why they are needed.

File 1: scripts/Start.js

```
The "entry point" for the webpack. Will tell the app what to do. 
```

File 2: config/Jest

```
A framework for testing React.
```

File 3: config/polyfills

```
A plugin that will provide the code needed to run in certain environments (a transpiler).
```

4\.  What does Webpack do? Explain, using specific examples from this activity.

```
The webpack makes it easier to manage bigger projects by bundling together a bunch of useful tools. In this case for example the webpack provided a testing environment (jest).
```
