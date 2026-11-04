# c-\_runtime_notebooks

# C# 기초 학습: 책 정리 및 챕터 화면 공부

해당 프로젝트는 C# 교과서를 참고해 챕터별로 읽고, Markdown으로 개념을 정리, C# 예제를 직접 작성하며 공부하는 레포다. 한 챕터를 마무 리하면 같은 Markdown을 문서 화면에 연결한다

학습 순서는 **책 관련 챕터 읽기 -> 개념과 원리 정리 -> 코드 작성 -> 실행 결과 비교 -> 등록**이다. 모던 딥다이브 책을 참고하여 절을 나누고, 개념·동작·원리·예제 해석을 연결하는 정리 방식을 사용. C# 학습 기준 책은 C# 교과서다.

새로 시작할 때는 아래처럼 시작한다

```bash
mkdir -p ~/Documents/c#-study
cd ~/Documents/c#-study
```

## 1. 구조

| 순번 | 위치             | 내용                        |
| ---- | ---------------- | --------------------------- |
| 1    | README.md        | 학습 흐름과 파일 역할       |
| 2    | part-01          | 책 1장 읽기 및 정리         |
| 3    | practice/part-01 | 예제 관련 직접 실행 및 작성 |
| 4    | note             | 관련 기록                   |

1장 전체 및 앞으로 있을 챕터들에 관련된 공부

## 실행 준비

터미널에서 확인

```bash
dotnet --info
dotnet --list-sdks
```

이 자료의 실행 프로젝트는 .NET 10 SDK와 net10.0을 기준으로 한다. SDK가 없으면 [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)를 설치한다. SDK가 아직 없어도 먼저 개념을 읽고 결과를 예상할 수 있다.

프로젝트를 직접 처음 생성한다면 아래를 실행한다. 이미 제공한 HelloWorld.csproj와 Program.cs를 배치했다면 생성 명령을 건너뛰고 빌드부터 한다.

## 참고

- [C# 교과서](https://thebook.io/006890/)
- [dotnet run](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-run)
- 문서의 링크·예제 분리·파일 배치를 확인했다. 작성 환경에 .NET SDK가 없어 실행 예제의 출력은 기존 코드 분석에 따른 예상 출력이며 실제 실행 결과는 학습 기록에 남긴다.
