# 100 Days Of Code - Log

### Day 1: June 20, 2017

**Today's Progress**: Fixed drag and drop functionality in Kanban App. Required some debugging and realized I was trying to use splice with the task name as the index (Stupid). Also fixed issue where task wasn't being removed from column's internal task array. Decided to add internal counter for number of tasks which was then used for a task's "taskPos" which was used when splicing the column's task array.

**Thoughts:** I made some silly mistakes, mainly because my code is becoming messy. I'm going to have to adopt a different pattern to keep track of everything and decrease the lines of code in the main js file. I started drafting some ideas for using the module patern.

**Link to work:** [Personal Kanban App](https://github.com/yutosin/personal-kanban-app/commit/ac8c3ddc613c239c1a07bc606976df90f5523351)

### Day 2: June 21, 2017

**Today's Progress**: Added more options to the task customization form. Also added a date picker for the due date using the html5 date input. Had to use a polyfill for Firefox and added a hacky way to display date picker over bootstrap modal. Planned more for refactoring and redesigning code.

**Thoughts:** Today was the first time I actually had to deal with cross-browser considerations which proved frustrating. I went through a couple polyfills thinking none of them worked only to realize the date picker wasn't appearing over the modal. Not as many lines of code today, but I did lay a lot of groundwork for improved functionality of the core app.

**Link to work:** [Personal Kanban App](https://github.com/yutosin/personal-kanban-app/commit/02bd410b03b7490f79a385c405397068437a3b71)

### Day 3: June 22, 2017

**Today's Progress**: I'm pretty tired so I'll just paste the summary from the commit
	
	-Added a bit of functionality for recurring tasks
	-Register category on task objects
	-Fixed polyfill issue

**Thoughts:** I think I'm starting to reach the extent of what I can do with VanillaJS. Feels like for everything I'm doing there exists an easier way. Also running into a lot of "architecture" problems. I have to sit and think about how each new line of code will affect all the other components. Which is normal I guess. But it makes my coding slower.

**Link to work:** [Personal Kanban App](https://github.com/yutosin/personal-kanban-app/commit/b7133694a76a03e2fc5fae2b1fb2357bf38a4815)