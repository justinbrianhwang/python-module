## numpy: Basic Concepts and Functions

### English Version

#### Basic Concepts
The `numpy` module is a fundamental package for scientific computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

1. **ndarray**: The primary data structure in `numpy`. It is a multidimensional array object that allows for efficient array operations.
2. **Broadcasting**: A powerful mechanism that allows `numpy` to work with arrays of different shapes during arithmetic operations.
3. **Vectorization**: Enables the execution of operations on entire arrays rather than element-wise, resulting in faster computations.

#### Key Functions in numpy
- **array()**: Creates an ndarray from any object exposing the array interface.
- **arange()**: Returns evenly spaced values within a given interval.
- **linspace()**: Returns evenly spaced numbers over a specified interval.
- **reshape()**: Gives a new shape to an array without changing its data.
- **ones()**: Generates an array of given shape and type, filled with ones.
- **zeros()**: Generates an array of given shape and type, filled with zeros.
- **eye()**: Generates a 2-D array with ones on the diagonal and zeros elsewhere.
- **sum()**: Returns the sum of array elements over a given axis.
- **mean()**: Returns the mean of the array elements along the specified axis.
- **dot()**: Dot product of two arrays.
- **sqrt()**: Computes the square root of each element in the array.
- **transpose()**: Transposes the axes of an array.

For more detailed information, refer to the official numpy documentation: [numpy Documentation](https://numpy.org/doc/)

### Korean

#### 기본 개념
`numpy` 모듈은 파이썬에서 과학 계산을 위한 기본 패키지입니다. 큰 다차원 배열과 행렬을 지원하며, 이러한 배열을 조작하기 위한 다양한 고수준의 수학 함수들을 제공합니다.

1. **ndarray**: `numpy`의 주요 데이터 구조입니다. 효율적인 배열 연산을 가능하게 하는 다차원 배열 객체입니다.
2. **브로드캐스팅**: `numpy`가 산술 연산 중에 서로 다른 모양의 배열을 작업할 수 있게 하는 강력한 메커니즘입니다.
3. **벡터화**: 요소별이 아닌 전체 배열에 대해 연산을 수행할 수 있게 하여 더 빠른 계산을 가능하게 합니다.

#### 주요 함수들
- **array()**: 배열 인터페이스를 노출하는 모든 객체로부터 ndarray를 생성합니다.
- **arange()**: 지정된 간격 내에서 균일하게 간격을 둔 값을 반환합니다.
- **linspace()**: 지정된 구간 내에서 균일하게 간격을 둔 숫자를 반환합니다.
- **reshape()**: 데이터는 변경하지 않고 배열에 새로운 모양을 부여합니다.
- **ones()**: 주어진 형태와 타입으로 모두 1로 채워진 배열을 생성합니다.
- **zeros()**: 주어진 형태와 타입으로 모두 0으로 채워진 배열을 생성합니다.
- **eye()**: 대각선은 1, 나머지는 0인 2차원 배열을 생성합니다.
- **sum()**: 주어진 축을 따라 배열 요소의 합계를 반환합니다.
- **mean()**: 지정된 축을 따라 배열 요소의 평균을 반환합니다.
- **dot()**: 두 배열의 점곱을 계산합니다.
- **sqrt()**: 배열의 각 요소에 대한 제곱근을 계산합니다.
- **transpose()**: 배열의 축을 전치합니다.

자세한 정보는 공식 numpy 문서를 참조하십시오: [numpy Documentation](https://numpy.org/doc/)
