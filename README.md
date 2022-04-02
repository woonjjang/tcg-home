## TCG Blog 를 작성합니다. 

1. hugo v0.95.0 / netlify

## Gitpod 사용하기 

1. Chrome Extention을 추가합니다. Gitpod에 가입하고, Github 레포지토리를 가져올 수 있도록 합니다. 
2. Github에서 https://github.com/features/codespaces 를 오픈하기 전까지 비슷한 위치에 있는 Gitpod 버튼을 클릭해서 instant dev environment 를 Gitpod 편집화면으로 가져옵니다. 

## netlify CMS

- 세팅 방법 https://www.netlifycms.org/docs/hugo/#creating-a-new-site
- config.yml 에 git-gateway 를 수정하지 않는다. 
- 아래 스크립트를 Front header에더 넣어줘야 netlify identy 에서 발송한 사용자별 token을 확인하고 접근 가능
```
<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
```

## build with netlify
- t.textconsulting.io
- 텍스트를 쓰는 일을 끄적인다.
- 연구의 output이 결국은 텍스트라 연구결과도 텍스트로 발행한다.

## build with vercel
- c.textconsulting.io
- 코드를 쓰는 일과 관계된 것을 적어본다.