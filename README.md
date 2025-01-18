# Firebase Firestore Data Not Written - Incorrect Path Issue

This repository demonstrates a common error when using Firebase Firestore:  data not being written to the database due to an incorrect path specified in the `set()` method.  The `firestoreBug.js` file shows the erroneous code, while `firestoreBugSolution.js` provides the corrected version.

## Steps to Reproduce

1. Clone this repository.
2. Make sure you have the Firebase CLI installed and configured (`firebase login`).
3. Install dependencies: `npm install`
4. Run the `firestoreBug.js` to observe the error.
5. Run the `firestoreBugSolution.js` to see the corrected behavior.

## Key Points

* Double-check your Firestore paths when using `set()` to ensure they correctly reflect your database structure.
* Use the Firebase console or other tools to inspect your database to verify data writes have succeeded.
* Leverage Firebase's error handling to catch and manage potential issues.
