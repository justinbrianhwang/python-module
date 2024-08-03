## os: Basic Concepts and Functions

### English Version

#### Basic Concepts
The `os` module in Python provides a way of using operating system-dependent functionality like reading or writing to the file system. It is part of the standard utility modules in Python and provides a portable way of using operating system-dependent functionalities.

1. **os.name**: The name of the operating system dependent module imported.
2. **os.sep**: The separator used by the operating system to separate pathname components.

#### Key Functions in os
- **getcwd()**: Returns the current working directory.
- **listdir()**: Returns a list of the entries in the directory given by path.
- **mkdir()**: Creates a directory named path with numeric mode mode.
- **rmdir()**: Removes the directory path.
- **remove()**: Removes (deletes) the file path.
- **rename()**: Renames the file or directory src to dst.
- **chdir()**: Changes the current working directory to the given path.
- **path.exists()**: Returns True if path refers to an existing path or an open file descriptor.
- **path.join()**: Joins one or more path components intelligently.
- **path.basename()**: Returns the base name of pathname path.

For more detailed information, refer to the official os documentation: [os Documentation](https://docs.python.org/3/library/os.html)

### 한국어 버전

#### 기본 개념
파이썬의 `os` 모듈은 파일 시스템에 읽고 쓰기 같은 운영 체제 종속 기능을 사용할 수 있는 방법을 제공합니다. 파이썬의 표준 유틸리티 모듈의 일부이며, 운영 체제 종속 기능을 사용할 수 있는 이식 가능한 방법을 제공합니다.

1. **os.name**: 임포트된 운영 체제 종속 모듈의 이름입니다.
2. **os.sep**: 경로명 구성 요소를 분리하기 위해 운영 체제에서 사용하는 구분자입니다.

#### 주요 함수들
- **getcwd()**: 현재 작업 디렉토리를 반환합니다.
- **listdir()**: 주어진 경로의 디렉토리 내의 항목 목록을 반환합니다.
- **mkdir()**: 지정된 경로에 디렉토리를 생성합니다.
- **rmdir()**: 지정된 경로의 디렉토리를 제거합니다.
- **remove()**: 지정된 경로의 파일을 삭제합니다.
- **rename()**: 파일 또는 디렉토리의 이름을 변경합니다.
- **chdir()**: 현재 작업 디렉토리를 지정된 경로로 변경합니다.
- **path.exists()**: 경로가 존재하는지 또는 열린 파일 서술자인지 여부를 반환합니다.
- **path.join()**: 하나 이상의 경로 구성 요소를 지능적으로 결합합니다.
- **path.basename()**: 경로의 기본 이름을 반환합니다.

자세한 정보는 공식 os 문서를 참조하십시오: [os Documentation](https://docs.python.org/3/library/os.html)
