# whatwasidoing
A todo list for multitaskers or single-celled organisms.

Keeps track of the **one thing** you should be focusing on in the current project directory.
Really a one line todo list for scatterbrains like Brian.

If you're like me, you have a bunch of different projects that you are messing with at any given time. The hardest part about having so many projects is remembering where you left off, and what is left to do. This is a simple tool that lets you create a single todo (for each project directory), recall what you were `doing`, then mark it as complete, or even commit the todo to git. 

### Installation:
```
git clone https://github.com/0xc00010ff/whatwasidoing.git
cd whatwasidoing
sudo make install
```

### Usage:
```
command-line $ doing refactoring the spacetime combobulator
> refactoring the spacetime combobulator

command-line $ doing
> 🔹 refactoring the spacetime combobulator

command-line $ doing done
> ✅ refactoring the spacetime combobulator

// or- commit straight to git. It's like building red/green tests on yourself.

command-line $ doing commit
> 🔮 Committing...
> *shows git commit editor with todo as default commit message*
> Done! Committed! ✨✅✨
```

* The todos are namespaced by directory, so your todo in ~/project1 is unaffected by that in ~/project2
