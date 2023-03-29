
# Application of GA on scheduling an actual Exam Schedule for IIITM Gwalior

## Group Project made by: <ul><li>Deep Jawale</li><li>Darshan Arkhade</li><li>Manav Jethva</li></ul>

### 1st Iteration 
 We went over the idea of how to actually implement a genetic algorithm for creating a schedule and found that rather than makin a binary decision variable we can use a Schedule class which would contain a fitness value and a dictionary for storing the classrooms used that day.
For developing the skeleton for the project we need to implement the following things:
- [ ] Code the basic structure of the decision variable/chromosome
- [ ] Write code for loading the data
- [ ] Get the data in the format used to get it inputted from real life
- [ ] Write code for functions for:
- - [ ] Generating random population
- - [ ] Checking constraints (If all are satisfied or not)
- - - [ ] Hard Constraints
- - - - [ ] H1 Exam is scheduled for each course
- - - - [ ] H2 Student can't give more than one exam at a time
- - - - [ ] H3 Teacher can't invigilate more than one exam at a time
- - - - [ ] H4 Student can't give consecutive exams in a day
- - - - [ ] H5 One course must be scheduled once only
- - - [x] Soft Constraints
- - - - [x] S1 Exam is scheduled in less days
- - - - [x] S2 Almost equal number of invigilation duties
- - [ ] Calculating fitness of a chromosome/schedule
- - [ ] Get two best fittest schedules
- - [ ] Selecting Parents (Roulette Wheel Selection)
- - [ ] Creating two children for two input parents using crossover (mix_days)
- - [ ] Mutating Schedule with a given mutation probablity
- - [ ] Applying crossover on the population using a given crossover probablity
- - [ ] Applying mutation on population using a given mutation probability
- - [ ] Applying GA
- - [ ] Printing utility functions
- - [ ] main()
- - - [ ] Utilize the printing function and a single call to the apply GA function to get the algo up and running.
