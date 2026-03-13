SCRIPT_DIR="$(cd "$(dirname "${BASH_SOURCE[0]}")" && pwd)"
docker build -t deepaudit/sandbox:latest -f ${SCRIPT_DIR}/Dockerfile ${SCRIPT_DIR}