
# π[ν¬λμ] κ·Ήμ₯ μ’μ λ¦¬λ·°μ¬μ΄νΈπ


## π ν¬λμ μκ° | About Us
![KakaoTalk_20221014_194653280](https://user-images.githubusercontent.com/109055420/195832976-26b88da4-3e04-4bf7-9282-b0d278444c66.png)


### κ·Ήμ₯ μ’μ?! μ’μ μλ¦¬λ μλ μνμ μ΅μ μ μ νμ?
![KakaoTalk_20221003_034649228](https://user-images.githubusercontent.com/109055420/193470896-90e12165-8d97-4437-becd-624c4b39415a.png)

π λλ§ μκ³  μλ μ’μ μ’μμ΄λ κΏ κ°μ μ’μμ κ³΅μ νκ³  μΆμΌμ  λΆ! </br>
π ν€ ν° μ¬λλ ν€ μμ μ¬λλ κ³΅μ°μ΄ λ€ λ³΄μ΄λ μλ¦¬λ₯Ό κ³΅μ νκ³  μΆμΌμ  λΆ !</br>
π κ·Ήμ₯ μ’μμ΄ μ΄λ»κ² λ³΄μΌμ§ λͺ¨λ₯΄κ² λ€λ©΄ ν¬λμμμ νμΈνμΈμ! </br>

- ν¬λμμ μ¨κ²¨μ§ κΏ μλ¦¬λ μ΅μ μ μ’μ μ νμ λμΈ μ μλ μΉ μ¬μ΄νΈ μλλ€.

### π μΉμ¬μ΄νΈ | Website  [ν¬λμ λ°λ‘κ°κΈ°](https://podoal.net)


<br>

## π­λͺ©μ°¨ | Contents
1. [κ°λ°κΈ°κ° | Project Period](#-κ°λ°κΈ°κ°--project-period)
2. [μν€νμ³ | Architecture](#-μν€νμ³--architecture)
3. [μ£Όμ κΈ°λ₯ | Main Function](#-μ£Όμ-κΈ°λ₯--Main-Function)
4. [κ°λ°νκ²½ | Development Enviornment](#-κ°λ°νκ²½--development-environment)
5. [λΌμ΄λΈλ¬λ¦¬ | Library](#-λΌμ΄λΈλ¬λ¦¬--library)
6. [ERD](#-erd)
7. [νΈλ¬λΈ μν| Trouble shooting](#-νΈλ¬λΈ-μν--trouble-shooting)
8. [ νμ | TEAM](#-νμ--team)

<br>



## β κ°λ°κΈ°κ° | Project Period
2022.08.26 ~ 2022.10.03 (6μ£Όκ°)

<br>

## π  μν€νμ³ | Architecture
![KakaoTalk_20221003_032628588](https://cdn.discordapp.com/attachments/457223932244656128/1026435122318290994/Architecture.png)


## β μ£Όμ κΈ°λ₯ | Main Function
### FE
- μμ λ‘κ·ΈμΈ (νΈμν° / μΉ΄μΉ΄μ€)
- μ€μκ° λ¦¬λ·° νμΈ (λ©μΈ νμ΄μ§ μ€μκ° λ¦¬λ·° SECTION)
- λ¦¬λ·° νκΈ° (CRUD) / λ¦¬λ·° λκΈ / μ’μμ κΈ°λ₯ / λ¦¬λ·° νμ΄μ§ λ¬΄νμ€ν¬λ‘€
- νκ·Έ, νν°, κ²μμ΄λ₯Ό ν΅ν κ²μ κΈ°λ₯
- νλ‘ν μμ 
- νλ‘ν λ΄μμ λ΄κ° μ΄ λ¦¬λ·° νμΈ
- κ·Ήμ₯ μ λ³΄ μΈν¬ MODAL (KAKAO MAP)
- λ°μν

### BE
- κ°νΈν μμ λ‘κ·ΈμΈ νΈμν°, μΉ΄μΉ΄μ€ν‘ μ§μ
- λ€μν κ²½μ°μ κ²μ μμ²­ μΌκ΄ μ²λ¦¬ (QueryDSL)
- μμ£Ό μ‘°ννλ λ°μ΄ν° μΊμ± μ²λ¦¬ (Redis, Spring Cache)
- λ°°ν¬λ μλ²μ μλ¬ λ‘κ·Έλ₯Ό μ½κ² νμΈ κ°λ₯ (Slack Webhook, Logback)
- RefreshToken ν ν°μ μ¬μ©νμ¬ λ‘κ·ΈμΈ μ λ³΄ μλ κ°±μ  (JWT)
- S3 μ€ν λ¦¬μ§μ μ μ₯λλ μ΄λ―Έμ§ λ¦¬μ¬μ΄μ§ μ²λ¦¬ (Imgscalr)
- CI/CD μλ λ°°ν¬ (Githib Action, S3, CodeDeploy)
- λ¬΄μ€λ¨ λ°°ν¬ (NGINX)


## β κ°λ°νκ²½ | Development Environment

<img  src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img  src="https://img.shields.io/badge/react query-FF4154?style=for-the-badge&logo=reactquery&logoColor=black">
<img  src="https://img.shields.io/badge/Recoil-0088CC?style=for-the-badge&logo=recoil&logoColor=white">
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
<img  src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
<img  src="https://img.shields.io/badge/styled-components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
<img  src="https://img.shields.io/badge/React Router-CA4245?style=for-the-badge&logo=React Router&logoColor=white">
<img  src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
<img  src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">
<img  src="https://img.shields.io/badge/aws Cloundfront-EF2D5E?style=for-the-badge&logo=&logoColor=white">
<img  src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
<img  src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
<img  src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
<img  src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
<img  src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=for-the-badge&logo=S&logoColor=white">
<img  src="https://img.shields.io/badge/Query DSL-4695EB?style=for-the-badge&logo=&logoColor=white">
<img  src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
<img  src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white">
<img  src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white">
<img  src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">
<img  src="https://img.shields.io/badge/Slack Webhook-4A154B?style=for-the-badge&logo=&logoColor=white">


## π¨ λΌμ΄λΈλ¬λ¦¬ | Library

     "@fortawesome/react-fontawesome": "^0.2.0",
     "axios": "^0.27.2",
     "file-loader": "^6.2.0",
     "json-server": "^0.17.0",
     "moment": "^2.29.4",
     "react": "^18.2.0",
     "react-dom": "^18.2.0",
     "react-hook-form": "^7.34.2",
     "react-intersection-observer": "^9.4.0",
     "react-query": "^3.39.2",
     "react-router-dom": "^6.3.0",
     "react-scripts": "5.0.1",
     "react-select": "^5.4.0",
     "react-toastify": "^9.0.8",
     "recoil": "^0.7.5",
     "styled-components": "^5.3.5",
     "sweetalert2": "^11.4.33",
     "sweetalert2-react-content": "^5.0.3",
     "swiper": "^8.3.2",
     

    

<br>

## π ERD 

![erd](https://cdn.discordapp.com/attachments/457223932244656128/1026447296243695697/unknown.png)


<br>


## π  νΈλ¬λΈ μν | Trouble shooting



<details>
<summary>(FE) μΉ νμ΄μ§ μ±λ₯ μ΅μ ν νκΈ°</summary>
<div markdown="1">
<span style="color:Red"> νΈλ¬λΈ μ΄μ</span>

![Untitled](https://user-images.githubusercontent.com/108280991/193574430-9f179b4f-1fe9-48d2-9459-6609e7669820.png)

lighthouseλ₯Ό μ΄μ©ν μ±λ₯ μΈ‘μ  κ²°κ³Ό μ±λ₯ λ° μ κ·Όμ±, κΆμ₯μ¬ν­μ μ μκ° λ§μ‘±μ€λ½κ² λμ€μ§ μμ ν΄λΉ μ¬ν­λ€μ μ λ¦¬νκ³ , κ°μ νκΈ°λ‘ κ²°μ .

<span style="color:Red"> νΈλ¬λΈ μν</span>

μ΄λ―Έμ§ λ λλ§ μκ°μ μ€μ΄κΈ° μν΄  

- μ°¨μΈλ νμμ μ¬μ©ν΄ μ΄λ―Έμ§λ₯Ό μ κ³΅ jpg, png > webpλ‘ λ³κ²½
- λμ  μ΄λ―Έμ§ μΊμ±μ²λ¦¬ μ§ν. s3, cloudfront μμ μΊμ± μ μ± λ³κ²½

<br>

λ©μΈνμ΄μ§ λ λλ§μ μ°¨λ¨μν€κ³  λ¦¬μμ€λ₯Ό λ¨Όμ  λ λλ§ νλ €λκ±Έ λ°©μ§.  
(λ¦¬μμ€ λ§ν¬μ asyncλ₯Ό λ£μ΄ κ°μ΄ λ‘λ© μν€λλ‘ν¨.)

<br>

μΉν°νΈκ° λ‘λ©λκΈ° μ κΉμ§ νμ€νΈκ° νμλμ§ μλλ‘ μ΅μ νλ₯Ό μ§νν¨.  
(font-display : swap;)

<br>

`lighthouse κ²°κ³Ό`  

![Untitled (1)](https://user-images.githubusercontent.com/108280991/193575940-42df99e7-2714-4249-90dd-3595916b5a01.png)


</div>
</details>

<details>
<summary>(FE) μ΄λ―Έμ§ λ λλ§ μλ κ°μ </summary>
<div markdown="2">
<span style="color:Red">νΈλ¬λΈ μ΄μ</span> 
<br> 
μ¬μ©μκ° λ¦¬λ·°νμ΄μ§ μ€ν¬λ‘€μ κ³μνλ€λ©΄ λ λλ§ν΄μΌ λ  
λ°μ΄ν°λ€μ΄ λ§μμ Έ λ λλ§ μλκ° λλ €μ§κ² λλ€. μ΄λ κ³³ μ¬μ©μ 
νΌλ‘λκ° μ¬λΌκ°κ² λλ―λ‘ μ¬μ΄νΈ μ΄νλ₯ μ΄ μ¬λΌκ°κ² λ κ²μ΄λ€

![image](https://user-images.githubusercontent.com/76687666/194465992-4136dbad-d021-4e27-8443-e471e337504e.png)


<span>ν΄κ²°</span>

react-virtualized λ₯Ό ν΅ν΄ νλ©΄μ λ³΄μ΄λ λΆλΆλ§ λ λλ§ νλλ‘ λ³κ²½

![image](https://user-images.githubusercontent.com/76687666/194467140-9b253168-b1b9-429c-a44e-6b6e061ee0cf.png)
![image](https://user-images.githubusercontent.com/76687666/194467197-e279236c-1b37-4b61-ba2e-92a282e2fcb5.png)

κΈ°μ‘΄μλ λ¦¬λ·°νμ΄μ§ μ μ²΄λ₯Ό λ λλ§νλ€λ©΄ νλ©΄μμ λ³΄μ΄λ 
λΆλΆλ§ λ λλ§ν΄ μ£Όλ λ°©μμΌλ‘ λ³κ²½

<span style="color:Red">κ²°κ³Ό</span>

![image](https://user-images.githubusercontent.com/76687666/194467349-1c231af3-443e-44d0-99ee-72841b644137.png)

λ λλ§ μλκ° 531.2ms β 18ms λ‘ κΈ°μ‘΄λ³΄λ€ κ°μνμλ€.



</div>
</details>


<details>
<summary>(BE) κ·Ήμ₯λ³ μ’μ μ‘°νμ λ°μ΄ν° μ²λ¦¬ μ±λ₯ κ°μ </summary>
<div markdown="3">
<span style="color:Red">λ¬Έμ μν©</span>  

- κ·Ήμ₯λ³ μ’μ μ λ³΄λ₯Ό λ€μκ³Ό κ°μ ννλ‘ νμ΄λΈμ μ μ₯νμμ΅λλ€.

| μ’μμμ΄λ | μΈ΅ | κ΅¬μ­ | μ΄ | μ’μλ²νΈ | κ·Ήμ₯μμ΄λ |
|--|--|--|--|--|--|
| 1 | FIRST | A | 1 | 8 | 1 |
| 2 | FIRST |A| 1 | 9 | 1 |

- κ·Ήμ₯μ μ’μ μ λ³΄ λ°μ΄ν°λ₯Ό json ννλ‘ κ°κ³΅νλ κ³Όμ μμ μ¬λ¬λ²μ μΏΌλ¦¬ νΈμΆμ΄ νμνκ³  μλ² μλ΅μ λ§μ μκ°μ΄ μμλμμ΅λλ€.

<span style="color:Red">μκ²¬μ‘°μ¨</span> 

1. mongoDB κ°μ NoSQL λ°μ΄ν°λ² μ΄μ€λ₯Ό μ¬μ©νμ¬ μ’μ μ λ³΄λ₯Ό json νμμΌλ‘ μ μ₯νκΈ°
2. μΊμλ₯Ό μ μ©νμ¬ λ°μ΄ν°λ² μ΄μ€ νΈμΆ νμλ₯Ό μ€μ΄κΈ°

- κ·Ήμ₯λ³ μ’μ μ λ³΄λ λ³κ²½μ΄ κ·Ήλλ‘ μ κ³  μ‘°νκ° λ§μ λ°μ΄ν° νΉμ±μ κ°μ§κ³  μμ
- μΊμλ₯Ό μ μ©νκΈ°λ‘ κ²°μ 

<span style="color:Red">κ²°κ³Ό</span>  
- JMeterλ₯Ό νμ©ν νμ€νΈ κ²°κ³Ό μ½ 90%μ μλ΅μκ° κ°μλ₯Ό νμΈν  μ μμμ΅λλ€.  

| λΌλ²¨ | νλ³Έμ | νκ· (ms) | μ΅μκ° | μ΅λκ° | νμ€νΈμ°¨ | μ€λ₯ |
|--|--|--|--|--|--|--|
| cache | 5000 | 341 | 5 | 725 | 156.5247 | 0 |
| noCache | 5000 | 3284 | 43 | 12071 | 1014.649 | 0 |

<br> 
</div>
</details>



<details>
<summary>(BE) κ·Ήμ₯λ³ μ’μ μ‘°νμ λ°μ΄ν° μ²λ¦¬ μ±λ₯ κ°μ </summary>
<div markdown="4">
<span style="color:Red">λ¬Έμ μν©</span>  

- JWT ν ν°μ ν¬ν¨νλ λͺ¨λ  μμ²­μ νν°μμ ν΄λΉ ν ν°μ κ²μ¦νλ κ³Όμ μ κ±°μΉ©λλ€.
- MemberRepositoryλ₯Ό ν΅ν΄ Member κ°μ²΄λ₯Ό μ°Ύμμμ UserDetailsλ₯Ό κ΅¬μ±νμλλ°

```Java
@Getter
@NoArgsConstructor
@AllArgsConstructor
public class UserDetailsImpl implements UserDetails {

    private Member member;
		...
}

@Service
@RequiredArgsConstructor
public class UserDetailsServiceImpl implements UserDetailsService {
    private final MemberRepository memberRepository;
    @Override
    public UserDetails loadUserByUsername(String subject) throws UsernameNotFoundException {
        Member member = memberRepository.findById(Long.parseLong(subject))
                .orElseThrow(() -> new UsernameNotFoundException("λ±λ‘λμ§μμ μ¬μ©μμλλ€."));
        return new UserDetailsImpl(member);
    }
}
```

- μ¬μ©μ κΆνμ΄ νμ μλ μμ²­μλ ν ν°μ΄ ν¬ν¨λμ΄μλ€λ©΄ UserDetailsλ₯Ό μμ±νλ κ³Όμ μμ λ°μ΄ν°λ² μ΄μ€λ₯Ό μ‘°ννμ¬ μλ΅μκ°μ΄ κΈΈμ΄μ§λ κ²μ νμΈνμμ΅λλ€.

<span style="color:Red">μμ λ°©ν₯</span>

1. JWT Tokenμ μλ²μμ SecretKeyλ₯Ό μ¬μ©νμ¬ μΈμ¦ν κ²
2. Tokenμ λ΄κΈ΄ μμ΄λλ ν ν°μ΄ μ ν¨νλ€λ©΄ μ νν κ²

- UserDetaileServiceλ₯Ό μ­μ νκ³ , UserDetailsImplμ Member κ°μ²΄ λμ  Idλ₯Ό μΆκ°νκ³ 

- JwtTokenProviderμμ μΈμ¦μ λ³΄λ₯Ό μ‘°νν  λ, JWT ν ν°μ Sub νλμ μ μ₯ν΄λ idκ°μΌλ‘ UserDetailsλ₯Ό μμ±νμμ΅λλ€.


```Java
@Getter
@NoArgsConstructor
@AllArgsConstructor
public class UserDetailsImpl implements UserDetails {

    private Long memberId;
		...
}

@Component
@Slf4j
@RequiredArgsConstructor
public class JwtTokenProvider {
		...
		public Authentication getAuthentication(String jwtToken) {
			  Claims claims = getClaims(jwtToken);
			  UserDetailsImpl userDetails = new UserDetailsImpl(Long.parseLong(laims.getSubject()));
			  return new UsernamePasswordAuthenticationToken(userDetails, "", userDetails.getAuthorities());
		}
		...
}
```

- κ°κ°μ μν°ν°λ€κ³Ό Member κ°μ²΄κ° λ§Ίμ μ°κ΄κ΄κ³λ μ κ±°ν νμ Auditing μμ±μ @CreatedBy @LastModifiedBy μ΄λΈνμ΄μμ μΆκ°νμμ΅λλ€.

```Java
@Getter
@MappedSuperclass
@EntityListeners(AuditingEntityListener.class)
public abstract class BaseEntity {

		...

    @CreatedBy // μμ±μ
    private Long createdBy;

    @LastModifiedBy //μμ μ
    private Long modifiedBy;
}

@RequiredArgsConstructor
@Component
public class LoginUserAuditorAware implements AuditorAware<Long> {

    @Override
    public Optional<Long> getCurrentAuditor() {
        Authentication authentication = SecurityContextHolder.getContext().getAuthentication();
        if (null == authentication || !authentication.isAuthenticated() || authentication.getPrincipal().equals("anonymousUser")) {
            return Optional.empty();
        }
        UserDetailsImpl userDetails = (UserDetailsImpl) authentication.getPrincipal();

        return Optional.ofNullable(userDetails.getMemberId());
    }
}
```

<span style="color:Red">κ²°κ³Ό</span>

- JMeterλ₯Ό νμ©ν νμ€νΈ κ²°κ³Ό μ½ 80%μ μλ΅μκ° κ°μλ₯Ό νμΈν  μ μμμ΅λλ€.


| λΌλ²¨ | νλ³Έμ | νκ· (ms) | μ΅μκ° | μ΅λκ° | νμ€νΈμ°¨ | μ€λ₯ |
|--|--|--|--|--|--|--|
| λ©€λ² κ°μ²΄ μ¬μ© | 5000 | 939 | 34 | 1893 | 199.3258 | 0 |
| Token idκ° μ¬μ© | 5000 | 125 | 7 | 382 | 53.45967 | 0 |


</div>
</details>

<br>

## π€Έπ»β νμ | TEAM

|  ![kimhun](https://cdn.discordapp.com/attachments/457223932244656128/1026470579328520222/Untitled-3_0001_Layer-5.png) | ![RIM](https://cdn.discordapp.com/attachments/457223932244656128/1026470580913971200/Untitled-3_0000_Layer-4.png)  | ![yelim](https://cdn.discordapp.com/attachments/457223932244656128/1026470579764736050/Untitled-3_0002_Layer-6.png) | ![suweon](https://cdn.discordapp.com/attachments/457223932244656128/1026470580138016839/Untitled-3_0003_Layer-7.png) | ![yongwon](https://cdn.discordapp.com/attachments/457223932244656128/1026470580473577483/Untitled-3_0004_Layer-3.png) |![YURI](https://cdn.discordapp.com/attachments/457223932244656128/1026476377265930301/Untitled-3_0000_Layer-5.png) |
|--|--|--|--|--|--|
|  κΉ ν| κΉνλ¦Ό  | κΉμλ¦Ό  | λ°μμ | λ°μ©μ | κΉμ λ¦¬ |
| BE(λ¦¬λ) | BE | FE(λΆλ¦¬λ) | FE | FE | DESINGER |
| [π](https://github.com/hunkim00) | [π](https://github.com/kimilm)| [π](https://github.com/97yelim) | [π](https://github.com/kksltv123) | [π](https://github.com/ParkYongWon) |[π](http://yurikim.net) |
