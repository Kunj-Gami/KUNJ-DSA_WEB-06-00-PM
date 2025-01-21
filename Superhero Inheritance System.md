# Superhero Inheritance System 💥✨

## Storyline:
In the world of superheroes, inheritance is the secret to sharing powers, abilities, and skills across different superheroes. But when multiple heroes have the same powers, there are ambiguities in the system. Your task is to create a Superhero Inheritance System in C++ that will:

- Teach the concepts of inheritance.
- Demonstrate the different types of inheritance (single, multiple, multilevel, hierarchical).
- Resolve ambiguities using the membership label operator (::).

---

## Task Description:

You will create a Superhero System using inheritance to share common abilities and powers between different superhero classes. The system should allow:

- Superheroes to inherit abilities from base classes.
- Ambiguities when multiple superheroes share the same powers to be resolved using the membership label operator.
- A grading system to rank superheroes based on their abilities.

---

### 1. Single Inheritance - Superhero Abilities (Base Class)

**Scenario:**  
Create a base class `Superhero` that has general abilities like flying and saving the world.

**Logic:**  
The `Superhero` class will have basic functions like `fly()` and `saveTheWorld()`.

**Task:**  
Create a class `Ironman` that inherits from `Superhero` and adds specific functionality like shooting lasers.

**Output:**  
Demonstrate Ironman flying and saving the world, using the inherited functions.

---

### 2. Multiple Inheritance - Flying and Fighting Heroes

**Scenario:**  
Create two base classes: `FlyingHero` and `FightingHero`. Both Ironman and Superman can fly, but only Ironman can shoot lasers.

**Logic:**  
Use multiple inheritance to allow Ironman and Superman to inherit from both `FlyingHero` and `FightingHero`.

**Task:**  
Ironman will have additional skills like shooting lasers, while Superman will have extra powers like heat vision.

**Output:**  
Both heroes should inherit the flying ability, but display their own unique fighting skills.

---

### 3. Multilevel Inheritance - Family of Heroes

**Scenario:**  
Batman is a skilled `FightingHero`, and his mentor `BruceWayne` is a `Superhero` (a richer, more powerful version of Batman).

**Logic:**  
The class `Superhero` will be inherited by `FightingHero`, which will then be inherited by Batman.

**Task:**  
Use multilevel inheritance to represent Batman’s evolution from his mentor BruceWayne.

**Output:**  
Display the powers of both BruceWayne and Batman, showing the inheritance hierarchy.

---

### 4. Hierarchical Inheritance - Many Heroes, One Base

**Scenario:**  
Create a base class `Superhero` and then derive different classes like Ironman, Superman, Batman, etc., from it.

**Logic:**  
All these superheroes will inherit basic powers from `Superhero` but will have their unique abilities.

**Task:**  
Each superhero will have their own abilities like flying, saving the world, or fighting villains.

**Output:**  
Display different superhero powers based on the class they belong to.

---

### 5. Resolving Ambiguity Using Membership Label Operator

**Scenario:**  
Both Ironman and Superman can fly, but when we call the `fly()` function, the system might get confused.

**Logic:**  
Use the membership label operator `::` to specify which class's `fly()` function should be used.

**Task:**  
Resolve the ambiguity by explicitly calling `Ironman::fly()` or `Superman::fly()` when both heroes can fly.

**Output:**  
Show which superhero's flying ability is executed.

---

### 6. Superhero Power Level and Grading

**Scenario:**  
Create a grading system to rank superheroes based on their power level, which is derived from their abilities.

**Logic:**  
The grading system works as follows:
- Power Level >= 100: "A1 - Top Hero"
- Power Level 75-99: "A2 - Very Good"
- Power Level 50-74: "B - Average Hero"
- Power Level < 50: "C - Needs Improvement"

**Task:**  
Based on superhero powers, assign a grade to each superhero.

**Output:**  
Display the power level and grade of each superhero.

---

## Hybrid Inheritance

### What is Hybrid Inheritance?

Hybrid inheritance is a combination of multiple types of inheritance in a single program. It is used when a class inherits properties from multiple base classes, and those base classes also inherit from other classes, creating a combination of multiple, multilevel, or hierarchical inheritance. This can be used to combine the benefits of all inheritance types and resolve conflicts or ambiguities.

In C++, hybrid inheritance can lead to ambiguity issues where two or more base classes have functions with the same name. To resolve these conflicts, we use the membership label operator `::` to specify which base class’s function should be called.

**Example in the Superhero System:**

- Suppose a superhero like `Ironman` inherits from both `FlyingHero` and `FightingHero`, while `FlyingHero` is itself derived from the `Superhero` base class. This results in a hybrid inheritance structure, as Ironman is inheriting both flying and fighting capabilities, and the base classes might share common methods, leading to ambiguities that need to be resolved.

---

## Requirements:

- **Single Inheritance:** Create a base class and a derived class.
- **Multiple Inheritance:** Combine multiple base classes into one derived class.
- **Multilevel Inheritance:** Use inheritance chains with more than two levels.
- **Hierarchical Inheritance:** Derive multiple classes from a single base class.
- **Hybrid Inheritance:** Use a combination of multiple inheritance types.
- **Ambiguity Resolution:** Resolve function ambiguity using the membership label operator `::`.
- **Grading System:** Create a grading system to rank superheroes based on their powers.
- **Use of Functions and Constructors:** Implement constructors to initialize powers and abilities.

---

## Submission Details:

- **Deadline:** January 25th, 2025, before 4:59 PM.
- Push your code to **GitHub** with proper comments.
- Include a screenshot of the final output.

---

## Evaluation Criteria:

- Proper use of inheritance types: single, multiple, multilevel, hierarchical, and hybrid.
- Correct usage of the membership label operator to resolve ambiguity.
- Accurate grading system based on superhero power levels.
- Creativity in designing unique superhero abilities.

---

## Note:

"This project will teach you how inheritance works in C++, and you’ll become the hero of your own programming world by mastering these concepts!" 💥
