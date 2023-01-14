# Text Consulting Group

## TCG Text 를 작성합니다. 

1. hugo v0.98.0+extended / netlify
2. twentynineteen-hugo theme를 불러옵니다.
```
git submodule update --init --recursive
```

## build with netlify
- content/texts
- t.textconsulting.io
- 텍스트를 쓰는 일을 끄적인다.
- 연구의 output이 결국은 텍스트라 연구 결과도 텍스트로 발행한다.

## build with vercel
- content/codes
- c.textconsulting.io
- 코드를 쓰는 일과 관계된 것을 적어본다.
- 관련된 설명에는 실제 코드를 잘 노출한다.


## netlify CMS

- 세팅 방법 https://www.netlifycms.org/docs/hugo/#creating-a-new-site
- config.yml 에 git-gateway 를 수정하지 않는다. 
- 아래 스크립트를 Front header에더 넣어줘야 netlify identy 에서 발송한 사용자별 token을 확인하고 접근 가능
```
<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
```

## Cloudflare R2

r2.textconsulting.io