# ft_transcendence

## Target

- ### Web
    - Major module: Use a Framework as backend. [1]
    - Minor module: Use a front-end framework or toolkit. [1.5]
    - Minor module: Use a database for the backend. [2]

- ### User Management
    - Major module: Implementing a remote authentication. [3] (krish)

- ### Gameplay and User Experience
    - Major module: Multiplayers (more than 2 in the same game). [4] (randy)

- ### AI Algorithm
    - Major module: Introduce an AI Opponent. [5] (krish/randy)

- ### Cybersecurity
    - Major module: Implement Two-Factor Authentication (2FA) and JWT. [6] (orestu)

- ### DevOps
    - Major module: Designing the Backend as Microservices. [7]

- ### Accessibility
    - Minor module: Multiple language supports. [7.5]

## Project Plan

1. ### Registration, Login, Login with 42
    - Email, Password, Display Name
    - Password Hased
    - SQL injections/XSS checking
    - https connection (with nginx)
    - form validation
    - ?secure routes?

2. ### Dashboard
    - Settings
        - change language (en, de, fr, es)
        - enable/disable 2FA
    
    - Play with a Friend
        - Same keyboard
    
    - Play with an AI
        - AI adapts
        - applies same rules for fairness

    - Multiplayer
        - Play with a friends (max 4)
        - Same Keyboard
    
    - Tournament
        - all local players (max 8)
    
    - Play Online with Random **(fallback)**
        - Play with an AI if no one is available

## Tournament Rules

1. Set Alias for all players
2. Random Match Making
3. 10 points to win or most points in 10 minutes
    - tie breaker: first to score
4. Winner moves to next round
5. unavailable players are disqualified

## Database Schema

1. User
    - id: int
    - name: string
    - email: string
    - password hash: string
    - 2FA: boolean
    - language: string/int

## Fallback Target Modules

- ### Gameplay and User Experience
    - Major module: Remote players.

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
