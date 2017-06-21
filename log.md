# 100 Days Of Code - Log

### Day 1: June 20, 2017

**Today's Progress**: Fixed drag and drop functionality in Kanban App. Required some debugging and realized I was trying to use splice with the task name as the index (Stupid). Also fixed issue where task wasn't being removed from column's internal task array. Decided to add internal counter for number of tasks which was then used for a task's "taskPos" which was used when splicing the column's task array.

**Thoughts:** I made some silly mistakes, mainly because my code is becoming messy. I'm going to have to adopt a different pattern to keep track of everything and decrease the lines of code in the main js file. I started drafting some ideas for using the module patern.

**Link to work:** [Personal Kanban App](https://github.com/yutosin/personal-kanban-app/commit/ac8c3ddc613c239c1a07bc606976df90f5523351)