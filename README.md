# Next.js 15 Uncaught ReferenceError Bug
This repository demonstrates a bug in Next.js 15 where an uncaught `ReferenceError` on a page results in a crash, without being handled by Next.js's error boundaries.  The issue occurs when a page attempts to access a variable that hasn't been defined.

## How to Reproduce
1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Navigate to `/about`.  You'll see the application crash with an error in the console.

## Solution
The solution involves either defining the variable or using proper error handling (try...catch). The provided `aboutSolution.js` demonstrates this by defining the variable.