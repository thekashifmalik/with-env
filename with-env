#!/usr/bin/env bash
set -eo pipefail -o allexport
source .env
bold=$(tput bold)
normal=$(tput sgr0)
echo "[with-env] Loaded ${bold}${PWD}/.env${normal}."
set +o allexport
exec "$@"
