## requests: Basic Concepts and Functions

### English Version

#### Basic Concepts
The `requests` module in Python allows you to send HTTP/1.1 requests easily. It abstracts the complexities of making requests behind a simple API, allowing you to send HTTP requests with a few lines of code.

1. **HTTP (HyperText Transfer Protocol)**: The foundation of data communication on the web.
2. **Request**: A call to a web server to retrieve or send data.
3. **Response**: The data sent back from the server in response to a request.

#### Key Functions in requests
- **get()**: Sends a GET request to a specified URL.
- **post()**: Sends a POST request to a specified URL.
- **put()**: Sends a PUT request to a specified URL.
- **delete()**: Sends a DELETE request to a specified URL.
- **head()**: Sends a HEAD request to a specified URL.
- **options()**: Sends an OPTIONS request to a specified URL.
- **Response.status_code**: Returns the status code of the response.
- **Response.text**: Returns the content of the response, in Unicode.
- **Response.json()**: Returns the JSON content of the response, if any.

For more detailed information, refer to the official requests documentation: [requests Documentation](https://docs.python-requests.org/en/master/)

### 한국어 버전

#### 기본 개념
파이썬의 `requests` 모듈은 HTTP/1.1 요청을 쉽게 보낼 수 있게 해줍니다. 복잡한 요청 과정을 간단한 API 뒤에 추상화하여 몇 줄의 코드만으로 HTTP 요청을 보낼 수 있습니다.

1. **HTTP (HyperText Transfer Protocol)**: 웹 데이터 통신의 기초입니다.
2. **요청**: 데이터를 검색하거나 보내기 위해 웹 서버에 호출하는 것입니다.
3. **응답**: 요청에 대한 응답으로 서버에서 보내는 데이터입니다.

#### 주요 함수들
- **get()**: 지정된 URL로 GET 요청을 보냅니다.
- **post()**: 지정된 URL로 POST 요청을 보냅니다.
- **put()**: 지정된 URL로 PUT 요청을 보냅니다.
- **delete()**: 지정된 URL로 DELETE 요청을 보냅니다.
- **head()**: 지정된 URL로 HEAD 요청을 보냅니다.
- **options()**: 지정된 URL로 OPTIONS 요청을 보냅니다.
- **Response.status_code**: 응답의 상태 코드를 반환합니다.
- **Response.text**: 응답의 내용을 유니코드로 반환합니다.
- **Response.json()**: 응답의 JSON 내용을 반환합니다(있을 경우).

자세한 정보는 공식 requests 문서를 참조하십시오: [requests Documentation](https://docs.python-requests.org/en/master/)
