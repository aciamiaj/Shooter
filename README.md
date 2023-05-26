# Shooter

The shooter spawning system is a code snippet that demonstrates the creation and spawning of shooter objects with different shooter models. It utilizes a shooter model factory to retrieve shooter models based on specified types and assigns them to shooter instances. The following steps outline the functionality of the code:

## Code Overview
The provided code snippet consists of the following components:

Printing Student Information: Prints the name and Humber ID of the student who wrote the code.

Shooter Model Factory: Creates an instance of the ShooterModelFactory and retrieves shooter models using the factory's GetShooterModel method. Three shooter models are created: "SpaceRanger", "Commando", and "Samurai".

Shooter Creation: Ten shooter objects are created using the retrieved shooter models. Each shooter is assigned a unique ID and a shooter model.

Spawning Function: The Spawn function is defined to print the ID, shooter, and associated skin and texture information for each created shooter.

## Usage
To use the shooter spawning system, follow these steps:

Ensure that the necessary dependencies and classes (ShooterModelFactory, IShooterModel, Shooter) are implemented and available.
Create an instance of the ShooterModelFactory using the Instance property.
Retrieve shooter models using the GetShooterModel method of the factory, specifying the desired shooter types.
Create shooter objects, providing the respective shooter model and a unique ID for each shooter.
Call the Spawn function to print the ID, shooter, and associated skin and texture information for each created shooter.

Please note that the above code is a simplified example demonstrating the usage of the shooter spawning system. The implementation may require additional code and dependencies to function correctly.

Please note that the above content is generated based on the provided code. It provides an overview of the shooter spawning system, its components, usage, and an example scenario.
