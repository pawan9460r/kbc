# Context for question.txt - Chemistry/Biology/Physics Quiz Application

## Overview
This repository contains a Python-based multiple-choice quiz application that tests knowledge across three main science subjects: Chemistry, Biology, and Physics. The quiz includes 33 questions covering various topics from these disciplines.

## Purpose
The application is designed to:
- Test and reinforce scientific knowledge
- Provide immediate feedback on answers
- Calculate and display final scores as percentages
- Serve as a study tool for students learning basic science concepts

## Technical Details

### Data Structure
- The questions are stored in a Python list called `question`
- Each question is a dictionary with the following keys:
  - `question`: The question text
  - `option1` through `option4`: Four answer choices (prefixed with numbers)
  - `answer`: The correct option number (1-4)

### Key Functions
1. **`correct_or_wrong(input_answer, answer)`**
   - Compares user's answer with correct answer
   - Increments mark by +1 for correct answers
   - Decrements mark by -1 for incorrect answers
   - Provides immediate feedback to the user

2. **`options(question_id)`**
   - Displays all four answer options for a given question
   - Formats output with numbered choices

### Scoring System
- Initial mark: 0
- Correct answer: +1 mark
- Incorrect answer: -1 mark
- Final score shown as percentage: `(mark/total_marks) * 100`

### Question Categories
The quiz covers:
- **Chemistry**: Chemical reactions, compounds, acids/bases, hydrocarbons
- **Biology**: Human anatomy, genetics, plant physiology, hormones
- **Physics**: SI units, electricity, optics, magnetism, atmospheric science

### Sample Questions Include
- Chemical properties (phenolphthalein color in acid, pH values)
- SI units (energy, current, resistance, power)
- Human biology (brain functions, blood circulation, digestion)
- Physics concepts (Ohm's law, lens types, light phenomena)
- Environmental science (global warming, ozone layer, biodegradability)

## Usage
The program runs continuously through all questions once. It:
1. Displays each question sequentially
2. Shows four numbered options
3. Prompts user for answer input (1-4)
4. Provides immediate correct/wrong feedback
5. Calculates and displays final percentage score

## Future Enhancements
Potential improvements could include:
- Question shuffling for different quiz versions
- Timed responses
- Difficulty levels
- Expanded question bank
- Answer review section
- Progress tracking
- Multiplayer mode

## Technical Requirements
- Python 3.x interpreter
- No external dependencies required

## Contributing
Contributions to expand the question bank, improve UI, or add new features are welcome. Please ensure new questions maintain the same data structure format.
