# OpenAPI-specifikation för bekräftabeslut BFF

Beskriver API:t mellan `rimfrost-regel-bekraftabeslut-fe` och `rimfrost-regel-bekraftabeslut-bff`.

- BFF:en implementerar det genererade interfacet från `rimfrost-regel-bekraftabeslut-bff-openapi-jaxrs-spec` (Maven).
- FE:n genererar TypeScript-typer med `openapi-typescript` från `openapi.yaml` på en release-tagg.
