# Damn Vulnerable NodeJS Application (DVNA) 

Damn Vulnerable NodeJS Application (DVNA) is a simple NodeJS application to demonstrate [**OWASP Top 10 Vulnerabilities**](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project#OWASP_Top_10_for_2013) and guide on fixing and avoiding these vulnerabilities. 

This version of DVNA is a fork of the original project https://github.com/appsecoo/dvna, but uses SQLite instead of MySQL

### Docker Compose setup

Clone the repository
```bash
git clone https://github.com/appsecco/dvna-sqlite; cd dvna
```

Start using docker compose
```bash
docker-compponse up
```

Access the application at http://localhost:9090

### Manual Setup

Clone the repository
```bash
git clone https://github.com/appsecco/dvna-sqlite; cd dvna
```

Install Dependencies
```bash
npm install
```

Start the application
```bash
npm start
```

Access the application at http://localhost:9090

## License

MIT
