# MyWebApp1

## 1 About

1. This repository can be used as base line for a cloud agnostic SAAS product.
2. Simple web application developed using [FastAPI][1].

> "FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints."
> 
> -- <cite>[FastAPI][1]</cite>

### 1.1 Features

This web application is developed to demonstrate below features:

1. ✅ RESTful API.
2. ✅ Database connection (MySQL).
3. ✅ Auth:
    1. **AuthN**: Authentication using username and password.
    2. **AuthZ**: Authorization using JWT (Algo: RS-256).
4. ✅ **RBAC**: Role Based Access Control.
5. ❌ Microservice Architecture.
6. ✅ Containerization using **Docker**.

### 1.2 Branch details

|  Branch  | DB connection| Auth | RBAC | Docker | Microservice |
|:--------:|:------------:|:----:|:----:|:------:|:------------:|
| `db_con` | ✅ | | | |
| `auth`   | ✅ | ✅ | | |
| `rbac`   | ✅ | ✅ | ✅ | |
| `docker` | ✅ | ✅ | ✅ | ✅ | |
| `micro`  | ✅ | ✅ | ✅ | ✅ | ✅ |
| `main`   | ✅ | ✅ | ✅ | ✅ | ✅ |


[1]: https://fastapi.tiangolo.com/
