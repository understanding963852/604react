# react에서는 이 데이터를 변할수 있는 값이며 값이 변할때마다 UI를 변경해 달라고(화면을 다시 그려달라) 알려야한다. 그럴때 사용하는것이 useState()이다.

```
const [num,setNum]=useState(0)
이 데이터를 변할수 있는 값 ==> num
num를 변하게 하는 함수 ==> setNum  --> 함수를 이용하여 num를 변경한다
useState(0)의 0은 num의 초기값

```


#  부분적으로 값 받기
![image](https://github.com/understanding963852/604react/assets/60366769/ccc19021-fd99-4c0f-afa0-c7238c0434c1)

```
import React from "react";

const Profile = ({img,name,title,isNew}) => {
  // || -->또는  A || B 둘중에 하나라고 True 이면 True
  // && --> 그리고 A && B  둘중에 하나라고 false 이면 false

  //console.log(props)
  // const img=props.img;
  // const name=props.name;
  // const title=props.title;
  // const isNew=props.isNew;


  //구조분해 destructure 
  //const {img,name,title,isNew}=props;

  return (
    <div className="profile">
      <img src={img} alt="avatar" />
      {/* {isNew?<span className="new">신입</span>:""} */}
      {isNew && <span className="new">신입</span>}
      <h2>{name}</h2>
      <p>{title}</p>
    </div>
  );
};

export default Profile;
```
