### Spring Cloud Config Repository

Spring Cloud Config Server에서 읽어드리는 설정 방식은 아래와같다.

```
/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
```

- 참고로 label은 Branch명이다.