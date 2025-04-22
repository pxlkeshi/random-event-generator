# 🏃‍♂️ Random Event & Training Day Generator

This JavaScript project demonstrates proper **variable scope** and includes functions that:
- Randomly assign an athletic event to a participant
- Return the required training days based on the selected event
- Log the event and training time for each participant

## 🧠 Concepts Practiced
- Function scope and variable declarations (`const`, `let`)
- Conditional logic
- Random number generation
- Function arguments and return values
- Console logging

## 🚀 How It Works

### Functions:

1. **`getRandEvent()`**
   - Randomly selects one of three events: `"Marathon"`, `"Triathlon"`, or `"Pentathlon"`.

2. **`getTrainingDays(event)`**
   - Returns the number of training days required for a given event:
     - Marathon: 50 days
     - Triathlon: 100 days
     - Pentathlon: 200 days

3. **`logEvent(name, event)`**
   - Logs a message with the participant's name and assigned event.

4. **`logTime(name, days)`**
   - Logs the number of training days the participant needs.

### Example Output:

```
Alice's event is: Marathon  
Alice's time to train is: 50 days  
Warren's event is: Pentathlon  
Warren's time to train is: 200 days
```

## 🛠 Usage

Run the script in a browser console or a Node.js environment:

```bash
node app.js
```

Make sure the variable scopes are correctly defined so that:
- `random` is scoped only where needed.

