## 0.0.2-dev.13

- Sort array before median calculation (#59 Closed)

## 0.0.2-dev.12

- Add operation created for Array2d (#48 Closed)

## 0.0.2-dev.11

- Enhance complex concat (#49 Closed)

## 0.0.2-dev.10

- PR #46 by myConsciousness merged (unnecessary imports removed and YML update)

## 0.0.2-dev.9

- `arange` moved to deprecated and replaced by `createArrayRange`, #39 closed
- some typos fixed

## 0.0.2-dev.8
- Issue Infinite loop, memory exhausted with PolyFit(x, y, degree) #37, solved
- some typos fixed

## 0.0.2-dev.7
- Typos in the Source Code

## 0.0.2-dev.6
- Performance improvements for Array.add

## 0.0.2-dev.5
- Array2d.fromArray is not deep copying the arrays in the list of arrays #31
- subArray2d and getColumn new methods 

## 0.0.2-dev.4
- singular value decomposition for matrix m != n (SVD)
- SVD bug to get U, V and S matrix fixed
- pseudo inverse matrix using Moore–Penrose (matrixPseudoInverse)
- new tests cases with matrix m != n
- new tests cases for SVD with matrix m != n
- matrixSub limit index added to avoid break
- array2dInverseOfEachElement bug for elements equal 0 fixed, just keep it 0

## 0.0.2-dev.3
- new array2d operations: array2dInverseOfEachElement, array2dPow

## 0.0.2-dev.2
- new array2d operations created: array2dAddToScalar, array2dDivisionToScalar, array2dMultiplyToScalar, array2dSubToScalar
- new array operation created: arrayAddToScalar
- new tests created for array and array2d operations

## 0.0.2-dev.1
- Null safety added to the package
- FFT bug to big power of 2 arrays fixed
- complexExp function created to calculate complex number natural exponent
- arrayConcat changed to concatenate N arrays

## 0.0.1-dev.12
- PR #22 merged: Remove unused dart: imports

## 0.0.1-dev.11

- Even and Odd number double check created;
- cross correlation for real and complex signals created;
- dartfmt applied in the code;

## 0.0.1-dev.10

- Even and Odd number int check created;
- matrix transpose bug fixed;
- classes documentations improved;

## 0.0.1-dev.9

- PolyFit issue #16;
- Dart lint warning fixed;

## 0.0.1-dev.8

- Logo url update.

## 0.0.1-dev.7

- License changed and documentation updates.

## 0.0.1-dev.6

- bug correction issue: https://github.com/scidart/scidart/issues/7 .

## 0.0.1-dev.5

- pubspec homepage updated.

## 0.0.1-dev.4

- README examples updated.

## 0.0.1-dev.3

- IO migrated to scidart_io.

## 0.0.1-dev.2

- Readme file updated.

## 0.0.1-dev.1

- NumDart, SciDart and IO fundamentals implemented and documented.
