

![image](https://github.com/understanding963852/604react/assets/60366769/049f156c-262a-4007-a008-265d6fa43f46)

# 🥯  Navigate 사용방법  -- 어떤 페이지로 강제로 이동(리다이렉트)
# react-router-dom 의 component


![image](https://github.com/understanding963852/604react/assets/60366769/40b60cea-bfbc-4408-b41b-640e512f44ef)


# 🚛   useParams   
# react-router-dom 의 hook

```
http://localhost:3000/product/1
```
#  url주소에서 파라미터는 제일뒤에있는 1이라는 숫자이다. id값이 들어와 있다.
#  파라미터값을 읽어와야할때 useParams   hook이다


![image](https://github.com/understanding963852/604react/assets/60366769/22e2b3a8-2aef-4b9a-8700-22324e179728)


# 문법  --> ?
```
<img src={product?.img} alt="" />

```
product?.img   ==> product가 있으면 product.img를 출력하라


# 🥗 쿼리 스트링

```
  쿼리스트링(query string)은 웹 주소(URL)에 추가적인 매개변수를 전달하는 방법 중 하나입니다.
 쿼리스트링은 URL의 끝에 "?" 문자로 시작하며, 이후에 "이름=값" 형태의 매개변수들이 "&" 문자로 구분되어 나열됩니다.

```


#  navigate(`/?q=${keyword}`)   --> 쿼리스트링(query string) 입력하기




















