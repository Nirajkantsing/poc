C:\Users\NirajkantSingh\Documents\Enhancement-Agentic\InsuranceSalesSystem_enhancementAgentic\InsuranceSalesSystem\scripts>python -m podman_compose -f springboot-app.yml up -d
STEP 1/8: FROM nginx
STEP 2/8: MAINTAINER ASC-LAB
--> Using cache c4208d480c20e83e60d7260a57143b4f83b22d68e11876e2b4d23e71b419f14f
--> c4208d480c20
STEP 3/8: ENV     GATEWAY_URL=${GATEWAY_URL:-http://localhost:8081}     AUTH_URL=${AUTH_URL:-http://localhost:8090}
--> Using cache d17817070c0dfec3cf7d35e27b42af2b18703360f467f68e7b0ed5cb2ef2c595
--> d17817070c0d
STEP 4/8: COPY ./dist /usr/share/nginx/html
Error: building at STEP "COPY ./dist /usr/share/nginx/html": checking on sources under "/mnt/c/Users/NirajkantSingh/Documents/Enhancement-Agentic/InsuranceSalesSystem_enhancementAgentic/InsuranceSalesSystem/web-vue": copier: stat: "/dist": no such file or directory

ERROR:__main__:Build command failed
