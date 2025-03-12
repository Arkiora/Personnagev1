# Character Game Simulation in Java
This project was developed as part of a Java programming course to demonstrate object-oriented programming concepts, including class design, encapsulation, and basic game mechanics. It simulates a simple character interaction system where characters (e.g., a sorcerer and a magician) can attack each other and manage their health.

## Key Features
- **Character Creation**: Create characters with a name and initial health points.

- **Health Management**: Characters can increase their health using the `AugmenterVie` method.

- **Attack Mechanism**: Characters can attack each other, reducing both the attacker's and the target's health.

- **Health and Name Retrieval**: Methods like `LaVie` and `LeNom` allow you to retrieve a character's health and name.

## Example Usage
```
Personnage UnSorcier = new Personnage("Sorcier", 70);
System.out.println("La vie du sorcier est " + UnSorcier.LaVie());

Personnage UnMagicien = new Personnage("Magicien", 100);
System.out.println("La vie du magicien est " + UnMagicien.LaVie());

UnSorcier.AugmenterVie(10);
System.out.println("Apres la vie du sorcier est " + UnSorcier.LaVie());

UnMagicien.Attaque(UnSorcier, 40);
System.out.println("Atak La vie du magicien est " + UnMagicien.LaVie());
System.out.println("Atak La vie du sorcier est " + UnSorcier.LaVie());
```

## Project Structure
- **Personnage.java**: Contains the `Personnage` class with methods for character creation, health management, and attacks.

- **jeuPersonnage.java**: A test class demonstrating the usage of the `Personnage` class, simulating interactions between characters.

## About This Project
This project was assigned as part of a Java programming course to help students learn and practice object-oriented programming concepts, including class design, encapsulation, and basic game mechanics. It serves as a practical example of how to model character interactions in a simple game-like environment.