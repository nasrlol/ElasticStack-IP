# ElasticStack-IP

## Prerequisites
- Docker
- Java 17 <
- Maven (optional)

## Start

1. **Clone the repository:**
	```bash
	git clone https://www.github.com/nasrlol/ElaticStack-IP.git
	cd ElasticStack-IP
	```

2. **Start Elasticsearch and Kibana:**
	```bash
	docker-compose up -d
	```
	- Elasticsearch: http://localhost:9200
	- Kibana: http://localhost:5601

3. **Build and run the application using Docker:**
	```bash
	docker build -t control-room-app .
	docker run --rm -p 8080:8080 control-room-app
	```
	- The app will be available at: http://localhost:8080

## Manual Build & Run (Without Docker)

1. **Install dependencies:**
	```bash
	mvn clean install
	```

2. **Run the application:**
	```bash
	mvn spring-boot:run
	```

## Configuration

## NOTE
> **Note:**
> This project is intended for demonstration and showcase purposes only. This is a throw away repository!
