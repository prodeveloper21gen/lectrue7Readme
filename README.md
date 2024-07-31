### 1. The `Date` Object
The `Date` object in JavaScript is used for working with dates and times. It allows you to create, manipulate, and format dates.

![image](https://github.com/user-attachments/assets/ac4a32e3-4e1e-42ad-ba13-1763895749bf)

#### Creating a `Date` Object
To create a new `Date` object, you can use the `new Date()` constructor. Here are a few examples:

```javascript
// Current date and time
let now = new Date();
console.log(now);

// Specified date and time
let specificDate = new Date('2024-07-31T12:00:00');
console.log(specificDate);

// Using numeric parameters (year, month, day, hour, minute, second, millisecond)
let anotherDate = new Date(2024, 6, 31, 12, 0, 0, 0);
console.log(anotherDate);
```
![image](https://github.com/user-attachments/assets/ef3c7ecf-7ed5-4759-9483-27bb75b27b4b)

#### Methods of the `Date` Object
The `Date` object comes with many methods for getting and setting different parts of a date and time.

**Methods for getting data:**
- `getFullYear()`: Returns the year (four digits).
- `getMonth()`: Returns the month (0-11).
- `getDate()`: Returns the day of the month (1-31).
- `getHours()`: Returns the hours (0-23).
- `getMinutes()`: Returns the minutes (0-59).
- `getSeconds()`: Returns the seconds (0-59).
- `getMilliseconds()`: Returns the milliseconds (0-999).

Example:

```javascript
let date = new Date();
console.log(date.getFullYear()); // 2024
console.log(date.getMonth()); // 6 (July, since months are 0-indexed)
console.log(date.getDate()); // 31
```

**Methods for setting data:**
- `setFullYear(year)`: Sets the year.
- `setMonth(month)`: Sets the month.
- `setDate(day)`: Sets the day of the month.
- `setHours(hours)`: Sets the hours.
- `setMinutes(minutes)`: Sets the minutes.
- `setSeconds(seconds)`: Sets the seconds.
- `setMilliseconds(milliseconds)`: Sets the milliseconds.

Example:

```javascript
let date = new Date();
date.setFullYear(2025);
date.setMonth(11); // December
date.setDate(25);
console.log(date); // 2025-12-25T...
```

### 3. Methods for Working with Dates: `get` and `set`
As mentioned earlier, `Date` objects have methods for getting (get) and setting (set) different parts of a date and time. Here’s a brief reminder of them:

![image](https://github.com/user-attachments/assets/24e88613-1d69-4436-8e90-1a4656ffe542)

#### Methods for getting (get):
- `getFullYear()`
- `getMonth()`
- `getDate()`
- `getHours()`
- `getMinutes()`
- `getSeconds()`
- `getMilliseconds()`

![image](https://github.com/user-attachments/assets/411b0a94-a3de-4ecc-a409-dbe1e8e45897)

#### Methods for setting (set):
- `setFullYear(year)`
- `setMonth(month)`
- `setDate(day)`
- `setHours(hours)`
- `setMinutes(minutes)`
- `setSeconds(seconds)`
- `setMilliseconds(milliseconds)`

Example of using all these methods:

```javascript
let date = new Date();
console.log(date.getFullYear()); // Get current year

date.setFullYear(2025); // Set new year
console.log(date.getFullYear()); // Check new year

console.log(date.getMonth()); // Get current month

date.setMonth(11); // Set new month (December)
console.log(date.getMonth()); // Check new month
```
