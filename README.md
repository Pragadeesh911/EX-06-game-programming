## EXP-06: Implement the AI random movement.

## Reg no:212224220073

## Aim:
 Implement the AI random movement.

 
## Algorithm:

Step:01 Create a Character Blueprint.


Step:02 Create a Blackboard.


Step:03 Open the Behavior Tree editor.


Step:04 Create Behavior Tree nodes for the following,
 "Selector" node: Controls the execution of child nodes.
 "Service" node: Monitors and updates values in the Blackboard.
 "Sequence" node: Executes child nodes in sequential order.
 "Random" decorator: Randomly selects a child node to execute.
 "Move To" task: Moves the AI character to a specified location.



Step:05 Set up the Blackboard with vector key and bool keys and save it.


Step:06 Set up the AI character Blueprint with the help of AI controller component.



Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AICharacter
Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”


Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to coverthe 
desired play area.
 
## Output:
![image](https://github.com/user-attachments/assets/73d166e9-2f8b-4aeb-9fb2-423f0f5ea385)

Blackboard Event graph:
![image](https://github.com/user-attachments/assets/7d54f4a2-c154-4534-86e8-7a8358b8db8f)


Behaviour Tree:
![image](https://github.com/user-attachments/assets/bb531c3b-f101-4c3e-9683-9175c20fcbce)


# Result:
Thus, the AI concept to the actor for a random movement is implemented.
