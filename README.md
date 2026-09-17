# Java Unit Converter

A console-based unit converter built in Java, supporting currency, temperature, and distance conversions through a simple menu-driven interface.

## Features

- **Currency Conversion**: INR to Dollar, Pound, Euro, Dirham, Mark, Yen
- **Temperature Conversion**: Celsius ↔ Fahrenheit
- **Distance Conversion**: Yards to Feet, Miles to Km, Km to Meter, Meter to Centimetre

## How It Works

The program presents a main menu where the user selects a conversion category, then a submenu for the specific conversion. Input is taken via the console and the converted result is printed immediately.

## Tech Used

- Java
- `Scanner` for console input

## How to Run

```bash
javac Compute.java
java Compute
```

Follow the on-screen menu prompts to select a conversion type and enter a value.

## Project Structure

- `Compute.java` — contains the main class and all conversion logic, organized into separate classes for currency, temperature, and distance conversions

## Notes

Exchange rates used for currency conversion are fixed values set in code, not fetched live — update `Currency_Method` if you need current rates.

## Future Improvements

- Fetch live exchange rates via an API instead of hardcoded values
- Add input validation for non-numeric entries
- Replace recursive menu navigation with a loop-based structure
