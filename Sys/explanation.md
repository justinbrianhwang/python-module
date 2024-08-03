## sys: Basic Concepts and Functions

### English Version

#### Basic Concepts
The `sys` module in Python provides access to some variables used or maintained by the Python interpreter and to functions that interact strongly with the interpreter. It is always available and provides tools for interacting with the system.

1. **sys.argv**: A list of command line arguments passed to a Python script. The first element is the script name.
2. **sys.version**: A string containing the version number of the Python interpreter.
3. **sys.path**: A list of strings that specifies the search path for modules.

#### Key Functions in sys
- **exit()**: Exits from Python. This function can be used to terminate a script.
- **getsizeof()**: Returns the size of an object in bytes.
- **setrecursionlimit()**: Sets the maximum depth of the Python interpreter stack.
- **getrecursionlimit()**: Returns the current value of the recursion limit.
- **platform**: Returns a string that identifies the underlying platform.

For more detailed information, refer to the official sys documentation: [sys Documentation](https://docs.python.org/3/library/sys.html)

### 한국어 버전

#### 기본 개념
파이썬의 `sys` 모듈은 파이썬 인터프리터에 의해 사용되거나 유지되는 일부 변수에 접근할 수 있게 하며, 인터프리터와 강력하게 상호 작용하는 함수들을 제공합니다. 항상 사용 가능하며 시스템과 상호 작용하는 도구를 제공합니다.

1. **sys.argv**: 파이썬 스크립트에 전달된 명령 줄 인수 목록입니다. 첫 번째 요소는 스크립트 이름입니다.
2. **sys.version**: 파이썬 인터프리터의 버전 번호가 포함된 문자열입니다.
3. **sys.path**: 모듈 검색 경로를 지정하는 문자열 목록입니다.

#### 주요 함수들
- **exit()**: 파이썬을 종료합니다. 이 함수는 스크립트를 종료하는 데 사용할 수 있습니다.
- **getsizeof()**: 객체의 크기를 바이트 단위로 반환합니다.
- **setrecursionlimit()**: 파이썬 인터프리터 스택의 최대 깊이를 설정합니다.
- **getrecursionlimit()**: 재귀 제한의 현재 값을 반환합니다.
- **platform**: 기본 플랫폼을 식별하는 문자열을 반환합니다.

자세한 정보는 공식 sys 문서를 참조하십시오: [sys Documentation](https://docs.python.org/3/library/sys.html)
