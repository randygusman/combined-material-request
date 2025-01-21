# combined-material-request

# Material Request Management System

A system to manage material requests with frontend and backend components.

## Frontend (Next.js)
- **Setup**:
  1. Clone the Repository: `git clone https://github.com/randygusman/combined-material-request.git`
  2. `cd frontend`
  3. Install dependencies: `npm install`
  4. Start the development server: `npm run dev`

## Backend (Spring Boot)
- **Setup**:
  1. Go to the backend folder: `cd backend`
  2. Install dependencies (if any): `./mvnw install` (or `mvn install`)
  3. Start the Spring Boot application: `./mvnw spring-boot:run` (or `mvn spring-boot:run`)

## Environment Configuration
- **Frontend**: Ensure that `NEXT_PUBLIC_API_BASE_URL` is set in `.env.local`.
- **Backend**: Update `application.properties` with your database configurations.
