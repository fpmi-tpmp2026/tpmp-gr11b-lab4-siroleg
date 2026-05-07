# Воздушный извозчик

## Project Name
Helicopter Fleet Management System (Variant 3)

## Description
Консольное приложение на языке C для управления авиаотрядом грузовых вертолётов.

Возможности:
- аутентификация пользователей
- роли: командир / член экипажа
- управление вертолётами
- управление рейсами
- просмотр экипажей
- расчёт зарплаты
- база данных SQLite

## Installation

git clone https://github.com/ervlader/helicopter-app-lab4.git
cd helicopter-app-lab4
sudo apt install -y gcc make sqlite3 libsqlite3-dev libcunit1-dev lcov
make
sqlite3 db/helicopter.db < db/schema.sql
sqlite3 db/helicopter.db < db/seed.sql

## Usage

./bin/helicopter

Пример входа:

login: commander
password: commander_pass

## Team

- Владислав — tests, Makefile, CI/CD, flights module
- Богдан — db/auth modules, documentation

## Repository

https://github.com/ervlader/helicopter-app-lab4



mkdir -p docs
nano docs/index.md



# Воздушный извозчик

Laboratory work #4

Helicopter Fleet Management System

## Team

- Владислав
- Богдан

## Links

Repository:
https://github.com/ervlader/helicopter-app-lab4
