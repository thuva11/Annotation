# Core - Config & Beans
 - @SpringBootApplication - Indicates to Spring this should adhere to Spring Boot autoconfig, by implying the following:
   - @Configuration or @SpringBootConfigration - Spring boot specific configs
   - @EnableAutoConfiguration - also spring boot's opinionated configs
   - @ComponentScan - set up bean config method to be component scanning
 - @EnableTransactionManagement - turns on transaction management infrastructure
 - @EnableAutoConfiguration
 - @Autowired
 - @Bean
 - @Configuration
 - @Component
 - @Service
 - @Controller
 - @Repository
 - @RestController
 - @Value
 - @Scope
 - @Qualifier


# Web - Controllers
 - @EnableWebMVC
 - @RequestMapping
 - @GetMapping is a Spring annotation that helps map HTTP GET requests to specific methods in a controller. It simplifies the process of handling GET requests in a web application, making it easy to define clean and readable URL paths for different functionalities. This annotation is commonly used in Spring MVC to create RESTful APIs, allowing developers to structure their code in a straightforward manner and handle GET requests efficiently.
 - @PutMapping
 - @PostMapping
 - @DeleteMapping
 - @PathVariable
 - @RequestParam
 - @RequestBody
 - @ResponseBody
 - @ResponeStatus
 - @RequestHeader
 - @ExceptinoHandler

# Data - Repos & Entities
 - @Transactional
 - @Query is used with Spring Data JPA to create custom queries for database operations. It allows you to define native SQL queries directly in your repository interface.

 - @Id
 - @Column
 - @GeneratedValue
 - @Table
 - @OneToMany
 - @ManyToMany
 - @OneToOne
 - @ManyToOne
 - @JoinColumn


# Unit Testing
 - @SpringBootTest
 - @DataJpaTest
 - @WebMvcTest
 - @MockBean

# AOP
 - @EnableAspectJAutoProxy
 - @Around
 - @Before
 - @After
 - @AfterReturning
 - @AfterThrows
 - @Aspect
 - @JoinPoint
 - @PointCut
