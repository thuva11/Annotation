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
 - @GetMapping
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
 - @Query
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
