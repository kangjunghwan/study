# 입문문자를 위한 Git 과 HTML&CSS
## 1일차
### CLI 명령어 학습
- mkdir(디렉토리생성)
- cd(디렉토리 이동)
- ls(디렉토리 목록 출력)
- rmdir(디렉토리 삭제)
- touch(빈파일 생성)
- echo(내용이 있는 파일 생성)
- cat(파일 내용 확인)
- rm(파일 삭제)
- mv(이동 및 이름 변경)
- cp(복사)

### Git 명령어 학습
-git status (현재 상태를 조회하기)
-git add (확정본을 만들기 위해 stage로 파일을 보내기)
-git commit -m(stage에 있는 파일의 확정본 생성하기)
-git log (변경 이력을 확인할 때)
-git tag (태그를 조회 하거나 추가하거나 삭제하기)


### 마크다운 문법 학습
[마크다운 정리](markdown.md)

## 2일차
HTML 관련 다양한 명령어를 실습을 통해 학습을 했습니다.
- DTD 선언(문서형 정의)

```html
<!DOCTYPE html>
```
- 제목과 단락요소
```html
<h1>...</h1>
<p>...</p>
```

- 텍스트 레벨의 시맨틱 요소
```html
<strong>...</strong>
<em>...</em>
<abbr>...</abbr>
```
- 목록 요소
```html
<ul>...</ul>
<ol>...</ol>
<dl>...</dl>
```

- 하이퍼링크와 이미지 요소             
>a 요소의 경우 이동하고자 하는 URL 또는 파일명을 href 속성에 명시하는 것이 필요하다. 그리고 해당 링크가 새창으로 보여지도록 할 경우 target 속성의 값으로 _blank를 지정하면 된다.
```html
<a>...</a>
<img>
```

- 테이블 요소
```html
<table>
<tr>
<th > ... </th>
<td> ... </td>
</tr>
</table>
```

- 폼 관련 요소
```html
<form>... </form>
<fieldset> ... </fieldset>
<legend> ... </legend>
<label> ... </label>
<input type ="?">
<textarea> ... </textarea>
<select> ... </select>
<button> ... </button>
```

- 인라인 프레임
<iframe src ="?"></iframe>
```

## 3일차
css 관련 다양한 속성을 실습을 통해 학습 했습니다.

-css 개념
-css를 적용하는 방법
-상속과 겹침
-css 선택자
-텍스트 관련 속성
-css 박스 모델
-flex 박스
-position과 float
-배경 관련 속성
-기타 다양한 속성(list-style 등)