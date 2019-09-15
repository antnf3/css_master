# css_master

## postcss-preset-env 설치

npm install postcss-preset-env

## postcss package.json 설정 추가

"postcss": {
"plugins": {
"postcss-preset-env": {
"stage": 0
}
}
}

## 빨간줄 뜨는건 VSCode에서 postcss문법 인식하는 extension 설치하시면 됩니다

https://github.com/MhMadHamster/vscode-postcss-language
I also recorded how to install : https://youtu.be/2LGVDxoRdN0

## postcss 속성

- matches
  li:matches(nth-child(even),.target){...}
- not
  li: not(.target){...}
- :root, var()
  :root {
  --commonColor: #f1c40f;
  --commonBorder: 1px solid red;
  }
  li:first-child a {
  background-color: var(--commonColor);
  border: var(--commonBorder);
  }

## 이미지 가져오기

https://www.pinterest.co.kr/
