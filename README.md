# DBAssignment2_MongoDB

## Introduction

I run the application on a local host machine, therefore I can not provide detailed information on how to run it on a Virtual Machine.

The code was written in jupyter notebook, so make sure you have that installed.

## How to run

Clone the repo, cd into the repo folder.
Download the csv file from http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip and extract it in the repo folder.

Run a mongodb instance on your local machine, make sure you have a connection. (If you are running this on a VM, follow instructions on https://github.com/datsoftlyngby/soft2019spring-databases/blob/master/lecture_notes/02-Intro_to_MongoDB.ipynb to see how to set it up on VM).

In a command line while in the repo folder, type jupyter notebook and open Mongo.ipynb to view the code and execute it.


## Output

### Question 1 How many Twitter users are in the database?

659774

### Question 2 Which Twitter users link the most to other Twitter users? (Provide the top ten.)

{'_id': 'lost_dog', 'links to others': 549}
{'_id': 'tweetpet', 'links to others': 310}
{'_id': 'VioletsCRUK', 'links to others': 251}
{'_id': 'what_bugs_u', 'links to others': 246}
{'_id': 'tsarnick', 'links to others': 245}
{'_id': 'SallytheShizzle', 'links to others': 229}
{'_id': 'mcraddictal', 'links to others': 217}
{'_id': 'Karen230683', 'links to others': 216}
{'_id': 'keza34', 'links to others': 211}
{'_id': 'TraceyHewins', 'links to others': 202}

### Question 3 Who is are the most mentioned Twitter users? (Provide the top five.)

Not implemented :(

### Question 4 Who are the most active Twitter users (top ten)?

{'_id': 'lost_dog', 'posts': 549}
{'_id': 'webwoke', 'posts': 345}
{'_id': 'tweetpet', 'posts': 310}
{'_id': 'SallytheShizzle', 'posts': 281}
{'_id': 'VioletsCRUK', 'posts': 279}
{'_id': 'mcraddictal', 'posts': 276}
{'_id': 'tsarnick', 'posts': 248}
{'_id': 'what_bugs_u', 'posts': 246}
{'_id': 'Karen230683', 'posts': 238}
{'_id': 'DarkPiano', 'posts': 236}

### Question 5 Who are the five most grumpy (most negative tweets) and the most happy (most positive tweets)?

{'negative': {'_id': 'lost_dog', 'count': 549},
              {'_id': 'tweetpet', 'count': 310},
              {'_id': 'webwoke', 'count': 264},
              {'_id': 'mcraddictal', 'count': 210},
              {'_id': 'wowlew', 'count': 210},
 'positive': {'_id': 'what_bugs_u', 'count': 246},
              {'_id': 'DarkPiano', 'count': 231},
              {'_id': 'VioletsCRUK', 'count': 218},
              {'_id': 'tsarnick', 'count': 212},
              {'_id': 'keza34', 'count': 211}}
