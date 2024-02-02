# Package Sorting Automation

Function for one of its robotic amrs that will dispatch the packages to the correct stack according to their volume and mass.

## How to run

Ensure you have a JavaScript runtime environment installed on your machine. If not, you can install Node.js.

Open a terminal or command prompt.

Clone this repository or download the package-sorting-automation.js file.

Navigate to the directory where the file is located.

E.G
```
cd package-sorting-automation
```
Open the file in your preferred code editor.

Modify the sort function parameters with the dimensions and mass of the package you want to test.

```
const package1 = sort(100, 80, 120, 15); // STANDARD
const package2 = sort(160, 90, 170, 19); // SPECIAL
const package3 = sort(200, 160, 180, 30); // REJECTED

console.log(package1)
console.log(package2)
console.log(package3)
```

Save the changes.

In the terminal, run the script using Node.js.

```
node package-sorting-automation.js
```
The script will output the stack name for the given package based on the implemented sorting criteria.

Repeat steps 6-9 with different package dimensions and masses to test different scenarios.
