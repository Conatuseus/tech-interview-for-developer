# Web(Spring)



#### Spring Framework란 무엇인가요? (정의, 특징 등)

> 

<br/>

<br/>

<br/>



#### Spring, Spring Boot, Spring MVC 차이는 무엇인가요

> 

<br/>

<br/>

<br/>

#### IoC에 대해 설명해주세요

> 

<br/>

<br/>

<br/>

#### IoC 컨테이너에 대해 설명해주세요

<br/>

<br/>

<br/>

#### Dispatcher Servlet에 대해 설명해주세요.

<br/>

<br/>

<br/>

#### AOP에 대해 설명해주세요

> AOP는 어플리케이션의 핵심적인 기능에서 부가적인 기능을 분리해서 애스펙트라는 모듈로 만들어서 설계하고 개발하는 방법입니다. 즉, 공통 부분을 모듈로 분리하는 것이며 주로 인증, 로깅, 트랜잭션 처리에 사용됩니다.

<br/>

<br/>

<br/>

#### AOP의 용어들에 대해 설명해주세요(Target, Aspect, Advice, PointCut, JoinPoint 등)

> Aspect: 애스펙트는 AOP의 기본 모듈이며, 애스펙트는 부가기능을 정의한 코드인 어드바이스(Advice)와 어드바이스를 어디에 적용하지를 결정하는 포인트컷(PointCut)을 합친 개념입니다.
>
> Target: 핵심 기능을 담고 있는 모듈로 타겟은 부가기능을 부여할 대상입니다.
>
> Advice: 어드바이스는 타겟에 제공할 부가기능을 담고 있는 모듈입니다.
>
> PointCut: 어드바이스를 적용할 타겟의 메서드를 선별하는 정규표현식입니다.
>
> Weaving: 위빙은 포인트컷에 의해서 결정된 타겟의 조인 포인트에 부가기능(어드바이스)를 삽입하는 과정을 뜻합니다.

<br/>

<br/>

<br/>

#### Filter와 Interceptor에 대해 소개해주세요

> Filter는 dispatcher servlet이 처리하기 전후에 동작하며, 요청 내용을 변경하거나 여러가지 체크를 할 수 있습니다. Interceptor는 스프링 컨텍스트 내부에 존재하여 컨트롤러의 전후에 동작하며 처리 작업을 할 수 있습니다. 인터셉터는 로그인 체크, 권한 체크 등의 처리가 가능합니다.

![Spring Flow 이미지](./image/spring_flow.png)

<br/>

<br/>

<br/>

#### DI에 대해 설명해주세요.

<br/>

<br/>

<br/>

#### Transaction의 처리 과정에 대해 설명해주세요

<br/>

<br/>

<br/>