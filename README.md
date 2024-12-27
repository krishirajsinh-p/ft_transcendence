# ft_transcendence

## Target

- ### Web
    - Major module: Use a Framework as backend. [1]
    - Minor module: Use a front-end framework or toolkit. [1.5]
    - Minor module: Use a database for the backend. [2]

- ### User Management
    - Major module: Implementing a remote authentication. [3]

- ### Gameplay and User Experience
    - Major module: Remote players. [4]

- ### AI Algorithm
    - Major module: Introduce an AI Opponent. [5]

- ### Cybersecurity
    - Major module: Implement Two-Factor Authentication (2FA) and JWT. [6]

- ### DevOps
    - Major module: Designing the Backend as Microservices. [7]

- ### Accessibility
    - Minor module: Multiple language supports. [7.5]

## Fallback Options

- ### Graphics
    - Major module: Use of advanced 3D techniques.

- ### Accessibility
    - Minor module: Expanding Browser Compatibility.
    - Minor module: Server-Side Rendering (SSR) Integration.

- ### Server-Side Pong
    - Major module: Replacing Basic Pong with Server-Side Pong and Implementing an API.

- ### DevOps
    - Major module: Infrastructure Setup for Log Management.
    - Minor module: Monitoring system.

- ### Cybersecurity
    - Major module: Implement WAF/ModSecurity with Hardened Configuration and HashiCorp Vault for Secrets Management.

## Project Plan

1. ### Registration, Login, Login with 42
    - Email, Password, Display Name
    - Password Hased
    - SQL injections/XSS checking
    - https connection (with nginx)
    - form validation
    - ?secure routes?

2. ### Home Page
    - Settings
        - change language (en, de, fr, es)
        - enable/disable 2FA
    
    - Play with a Friend
        - Same keyboard
    
    - Play with an AI
        - Set Random alias for AI
        - AI adapts
        - applies same rules for fairness
    
    - Play Online with Random
        - Play with an AI if no one is available
    
    - Tournament
        - List of tournaments with time and date
        - Create/Delete tournament
        - Join a tournament

## Game Rules

1. Set Alias
2. Random Match Making (if applicable)
3. 10 points to win or most points in 10 minutes
    - tie breaker: first to score

## Database Schema

1. User
    - id: int
    - name: string
    - email: string
    - password hash: string
    - 2FA: boolean
    - language: string/int

2. Tournament
    - id: int
    - name: string
    - time: datetime
    - players: int
    - winner: int