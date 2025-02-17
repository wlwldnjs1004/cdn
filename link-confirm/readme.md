# Link-Confirm 라이브러리

라이브러리에 대한 간단한 설명

## installation

 이 라이브러리는 jsdelivr cdn 을 사용합니다.
'<head>'

반드시 jQuery가 먼저 불러와져야 합니다



 ```html
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/wlwldnjs1004/cdn/link-confirm/index.js">  </script>
 ```

 ## usage

 확인창을 출력하고 싶은 '<a>' 태그에 '.link-confirm' 이라는 클래스를 부여하여 사용할수 있습니다

 ``` html
  <a href="https://google.com" class"link-confirm">구글로 이동</a>

  ```

위와 같이 작성하면 '정말 이동하시겠습니까?' 라는 메세지가 나옵니다

만약 사용자에게 보여줄 코멘트를 바꾸고 싶다면 'data-comment' 라는 속성을 추가할 수 있습니다.

```html
<a href="#" class"link-confirm" data-comment="정말 삭제하시겠습니다?">
