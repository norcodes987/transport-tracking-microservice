# Kubernetes Microservice architecture for a Transportation Tracking Company

Position Simulator: simulate vehicles moving around the country (runs test files in a loop)

ActiveMq: Receives simulated positions from Position Simulator

Position Tracker: Read the positions from the queue and do calculations based on it e.g. distance travelled

API Gateway: single point of entry into the application. Delegate frontend calls to the appropriate microservice

Webapp: Frontend portal implemented in Angular JS