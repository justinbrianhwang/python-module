## re: Basic Concepts and Functions

### English Version

#### Basic Concepts
The `re` module in Python provides support for regular expressions, which allow for powerful string pattern matching and manipulation. Regular expressions are used to search, match, and manipulate strings based on specific patterns.

1. **Pattern**: A regular expression pattern is a special sequence of characters that define a search pattern.
2. **Match**: An object containing information about the search and the result, if a pattern is found.

#### Key Functions in re
- **match()**: Determines if the RE matches at the beginning of the string.
- **search()**: Scans through a string, looking for any location where the RE matches.
- **findall()**: Finds all the matches of the RE in the string and returns them as a list.
- **finditer()**: Finds all the matches of the RE in the string and returns them as an iterator of match objects.
- **sub()**: Replaces the matches with a string.
- **split()**: Splits the string by the occurrences of the pattern.
- **compile()**: Compiles a regular expression pattern into a pattern object.

For more detailed information, refer to the official re documentation: [re Documentation](https://docs.python.org/3/library/re.html)

### 한국어 버전

#### 기본 개념
파이썬의 `re` 모듈은 정규 표현식을 지원하여 강력한 문자열 패턴 매칭 및 조작을 가능하게 합니다. 정규 표현식은 특정 패턴을 기반으로 문자열을 검색, 매칭 및 조작하는 데 사용됩니다.

1. **패턴**: 정규 표현식 패턴은 검색 패턴을 정의하는 특수 문자 시퀀스입니다.
2. **매치**: 패턴이 발견되면 검색 및 결과에 대한 정보를 포함하는 객체입니다.

#### 주요 함수들
- **match()**: 문자열의 시작 부분에서 정규 표현식이 일치하는지 확인합니다.
- **search()**: 문자열을 검색하여 정규 표현식이 일치하는 위치를 찾습니다.
- **findall()**: 문자열에서 정규 표현식의 모든 일치를 찾아 리스트로 반환합니다.
- **finditer()**: 문자열에서 정규 표현식의 모든 일치를 찾아 매치 객체의 이터레이터로 반환합니다.
- **sub()**: 일치하는 패턴을 다른 문자열로 대체합니다.
- **split()**: 패턴이 발생하는 곳을 기준으로 문자열을 분할합니다.
- **compile()**: 정규 표현식 패턴을 패턴 객체로 컴파일합니다.

자세한 정보는 공식 re 문서를 참조하십시오: [re Documentation](https://docs.python.org/3/library/re.html)
