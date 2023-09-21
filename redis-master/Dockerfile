# Use the official Redis base image
FROM redis:latest

# Expose the Redis default port
EXPOSE 6379

# Optional: Set a custom Redis configuration file
COPY redis-master.conf /usr/local/etc/redis/redis.conf

# Run Redis in master mode
CMD ["redis-server"]