c275-fall2019-first-git      
Create java files to make this code compile and run.      
What five objects are created in the main?
There are three dog Object, a List object, and the comparator Object that are called in the main

Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
Yes, it is the line: Collections.sort(dogs, new Comparator<Animal>() {
The class definition is found in the following code:
@Override                         
	public int compare(Animal a,Animal b){ 
		return a.getLegs() - b.getLegs();                         
		}                 
	});
