
# useEffect

# useEffect(()=>{},[])

# useEffect(()=>{},[])  ==> 배열이 비어있을 경우에는 component가 실행될때 처음 한번만 실행된다.
![image](https://github.com/understanding963852/604react/assets/60366769/e3ba505a-5e99-4c32-9b6d-998ec2576f67)

# useEffect(()=>{},[products])  ==>component가 실행될때 처음 한번 실행된후 products의 값이 바뀔때마다 useEffect가 실행됨
![image](https://github.com/understanding963852/604react/assets/60366769/15d3e6c0-7b11-4745-93b9-7be7e714feff)


# useEffect(()=>{},[products, count])  ==>component가 실행될때 처음 한번 실행된후 products와 count중 하나라도 값이 바뀌면 useEffect가 실행됨(2개 다 바뀌어도 한번만 실행됨)
