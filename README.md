# Expo CLI Build/Start Failure: Obscure Dependency Errors

This repository demonstrates a common yet frustrating issue when using the Expo CLI: build or start failures due to subtle problems with project dependencies, resulting in vague error messages.

The `bug.js` file represents a project with a problematic `package.json` – either missing, incorrect versions, or conflicting dependencies. This may lead to cryptic errors during `expo start` or `expo build`.  The solution is provided in `bugSolution.js`.

**How to reproduce:**
1. Clone this repository.
2. Navigate to the directory.
3. Try running `expo start`. Observe the error.
4. Examine the `package.json` file in `bug.js` to see the problematic dependency configuration. 
5. Compare to `package.json` in `bugSolution.js` to see how to correct it.
6. Run `expo start` again after applying the changes.  The application should now start successfully.