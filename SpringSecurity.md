# 🔐 Spring Security – Topics to Learn

---

## 📘 1. Introduction to Spring Security
- What is Spring Security?
- Importance of securing applications
- How Spring Security integrates with Spring Boot
- Core concepts: Authentication vs Authorization

---

## 👤 2. Authentication
- Username/Password authentication
- `UserDetails` and `UserDetailsService`
- `AuthenticationManager` and `AuthenticationProvider`
- In-memory authentication
- JDBC-based authentication
- Custom login pages

---

## 🔑 3. Authorization
- Role-based Access Control (RBAC)
- `@Secured`, `@PreAuthorize`, `@PostAuthorize`
- Method-level security
- URL-based authorization (using `HttpSecurity`)
- Custom permission evaluators

---

## 💥 4. Security Filters and Chain
- Spring Security Filter Chain
- Default filters overview
- Custom security filters
- How filters process requests and responses

---

## 📋 5. Form Login & Basic Authentication
- Spring Security default login form
- Custom login and logout endpoints
- Basic authentication setup
- CSRF protection and disabling it for APIs

---

## 🔐 6. JWT (JSON Web Tokens) Authentication
- Stateless authentication concept
- Creating JWT tokens and signing
- Validating tokens in filters
- Token expiration and refresh
- Secure storage of JWT secret keys

---

## 🌐 7. OAuth2 and OpenID Connect
- What is OAuth2?
- Spring Security OAuth2 Client
- Login with Google, GitHub, etc.
- Custom OAuth2 providers
- Scopes, consent screens, and access tokens

---

## 🔒 8. Password Encoding & Security
- `PasswordEncoder` interface
- Using `BCryptPasswordEncoder`
- Secure password storage best practices

---

## 🧪 9. Testing with Spring Security
- Testing secured endpoints
- Mocking authentication with `@WithMockUser`
- Testing with JWT/OAuth2 tokens

---

## 🔁 10. Security for REST APIs
- Stateless security setup
- Disabling session management
- Securing APIs with JWT
- CORS configuration for APIs

---

## ⚙️ 11. Security Configuration (Java Config)
- Using `SecurityFilterChain` with Spring Boot 3+
- Older `WebSecurityConfigurerAdapter` (deprecated)
- Ordering multiple security configurations
- Custom `AuthenticationProvider` setup

---

## 🚨 12. Exception Handling in Security
- Custom AccessDeniedHandler
- Custom AuthenticationEntryPoint
- Error messages and status codes

---

## 🛠️ 13. Advanced Topics (Optional)
- Multi-factor authentication (MFA)
- Remember-me functionality
- Session fixation and concurrent sessions
- Custom login flows and UI integration
- Integration with LDAP and SSO
"""
