Spring Boot Redis Project

Features:
- Users
- Posts
- Comments
- Like system (Redis)
- Virality scoring

Thread Safety:
- Redis INCR used for atomic counters
- Redis SET used for preventing duplicate likes

Run:
1. Start docker-compose
2. Run Spring Boot app
3. Test APIs using Postman
