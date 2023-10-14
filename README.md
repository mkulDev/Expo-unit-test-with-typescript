## How to Set Up Expo with Jest and TypeScript (Oct 2023)
I lost some time to setup Jest in Expo with TypeScript, so here you have a simple guide.


## 1. Install Dependencies
First, install the necessary packages as dev dependencies using your package manager.

    "@testing-library/jest-native"
    "@testing-library/react-native"
    "@types/jest"
    "ts-jest"
    "jest"
    "jest-expo"
    
Paste following line to the terminal:

`npm install --save-dev @testing-library/jest-native @testing-library/react-native @types/jest ts-jest jest jest-expo`

## 2. Update Your package.json
~~~
{
  "scripts": {
    "test": "jest"
  },
  "jest": {
    "preset": "jest-expo"
  }
}
