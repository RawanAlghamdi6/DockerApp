# Use the official PostgreSQL image from Docker Hub
FROM postgres:alpine

# Environment variables for PostgreSQL configuration
ENV POSTGRES_USER=rawan
ENV POSTGRES_PASSWORD=mypass
ENV POSTGRES_DB=mydatabase

# Mount a volume for persistent data storage
VOLUME /var/lib/postgresql/data

# Expose the PostgreSQL port
EXPOSE 5432
