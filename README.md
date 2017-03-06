# Passport Auth Demonstration

A minimalist exploration of how to get passport auth set up.

## Installation

You should have git and node and npm installed.

```bash
git clone git@github.com:esmevane/passport-auth-playground
cd passport-auth-playground
npm i
```

## Usage

Another really straightforward setup demonstration.  This time the server will keep track of some account details and allow signup, signin, signout, and two urls - one which works no matter what and another which only works when you use the JWT provided.

### Start the server:

```bash
npm start
```

### Sign up

```bash
bin/sign up --email "esmevane@gmail.com" --password "password"
```

### Sign in

```bash
bin/sign in --email "esmevane@gmail.com" --password "password"
```

### Sign out

```bash
bin/sign out
```

### Ping

```bash
bin/sign ping
```

### Secret Ping

```bash
bin/sign secret-ping
```
