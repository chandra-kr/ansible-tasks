# Task 1

## Skills required
- YAML parsing
- Basic ansible

## Task
Create an ansible playbook which will take a file as input and return the following:

### Example-1
If `sample1.yml` is the input file, it returns files in the following format:
- randomkey1.yml with the value
  ```
  randomvalue1
  ```
- randomkey2.yml with the value 
  ```
  randomvalue2
  ```
- randomkey3.yml with the value 
  ```
  randomvalue3
  ```

### Example-2
If `sample1.yml` is the input file, it returns files in the following format:
- WilliamShakespeare.yml with the value
  ```
  A rose by any other name would smell as sweet.
  All that glitters is not gold.	
  All the world’s a stage, and all the men and women merely players.	
  ```
- Bible.yml with the value
  ```
  Ask, and it shall be given you; seek, and you shall find.	
  For those to whom much is given, much is required.	
  The love of money is the root of all evil.	
  ```
- AbrahamLincoln.yml with the value
  ```
  Whatever you are, be a good one.	
  You can fool all of the people some of the time, and some of the people all of the time, but you can't fool all of the people all of the time.	
  ```

## Considerations
1. The input file sample1.yml can be dynamic in nature and can have as many elements inside the helloworld key
2. Ensure proper usage of variables where deemed necessary
