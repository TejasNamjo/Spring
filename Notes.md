# Spring

Although automatic Spring configuration with component scanning and automatic wiring is preferable in many cases, there are times when automatic configuration isn’t an option and you must configure Spring explicitly. For instance, let’s say that you want to wire components from some third-party library into your application. Because you don’t have the source code for that library, there’s no opportunity to annotate its classes with @Component and @Autowired. Therefore, automatic configuration isn’t an option.

In that case, you must turn to explicit configuration. You have two choices for explicit configuration: Java and XML.

@Component – Indicates a auto scan component.
@Repository – Indicates DAO component in the persistence layer.
@Service – Indicates a Service component in the business layer.
@Controller – Indicates a controller component in the presentation layer.

#Spring security check
Authentication
Authorizaion
session management
CSRF (forgery attack)
CORS
logout


