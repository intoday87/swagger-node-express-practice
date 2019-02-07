# Swagger-node로 express와 연동해보기

API 명세를 위해 node와 궁합이 맞는 모듈을 찾아보다가 swagger가 자바 개발자에게도 대중적이기 때문에 node로 API 서버를 구성하는 경우 얼마나 궁합이 잘 맞는지 확인해본다

## Swagger-node
- [Swagger-node 링크](https://github.com/swagger-api/swagger-node)
- [Swagger-node로 express와 연동 및 swagger-ui 연동 블로그](http://blog.jeonghwan.net/swagger-node/)

## Swagger-editor
- global로 swagger-editor를 설치하지 않으면 스켈리톤 프로젝트 생성시 swagger project '프로젝트명' 호출시 404(not found)가 발생
    - [이슈 링크](https://github.com/swagger-api/swagger-node/issues/480#issuecomment-437602190)

```bash
$ yarn global add swagger-editor
```
