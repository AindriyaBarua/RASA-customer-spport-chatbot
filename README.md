<p align="center"><img src="./assets/bot.png" width="10%"></p>
<h1 align="center">Customer Care Bot</h1>
<p align="center">Customer care bot for ecomm company which can solve FAQ and basic conversations with users, can contact directly to team.</p>

## Features
- [x] Basic E-commerce FAQ
- [x] Basic chitchats
- [x] Out of Scope
- [x] Contact us form
- [x] Send Emails

## Quick Setup
- Initialize a virtual environment via:
- Conda:
```bash
conda create --name rasaenv python=3.7
```
- virtualenv
```bash
virtualenv -p python3.7 rasaenv
```
- use pipenv
```
cd /customer-care-chatbot
pipenv install
```
- Install Rasa
```bash
python -m pip install -U pip
pip install rasa
```

## Testing
- Train bot
```
rasa train
```
- Test bot on shell
```
rasa shell
```
- start `rasa` server
```bash
rasa run --enable-api --cors "*" --debug[Optional] -p {PORT}[optional]
```
- start `actions` server
```
rasa run actions -p {PORT}[Optional]
```
