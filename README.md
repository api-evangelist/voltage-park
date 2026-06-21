# Voltage Park (voltage-park)

Voltage Park is a GPU cloud offering on-demand and reserved NVIDIA H100 and H200 clusters as bare metal and virtual machines. Its On-Demand API (served at cloud-api.voltagepark.com, running on TensorDock infrastructure) lets developers deploy and manage instant VMs, bare-metal GPU rentals, SSH keys, shared storage, and billing programmatically with bearer-token authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/voltage-park/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/voltage-park/refs/heads/main/apis.yml)

## Tags

- GPU
- Cloud
- AI Infrastructure
- H100
- H200
- Bare Metal

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Voltage Park Virtual Machines API

Deploy, list, modify, power-cycle, relocate, port-forward, and terminate on-demand GPU virtual machines, including preconfigured instant VMs provisioned in seconds from location presets.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- Virtual Machines
- Instances
- On-Demand

#### Properties

- [Documentation](https://docs.voltagepark.com/on-demand/deploy-gpus/virtual-machines-vms)
- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voltage Park Bare Metal & Clusters API

Provision and manage multi-node bare-metal H100/H200 GPU rentals in counts of eight, including power control, reboot, node removal, and Kubernetes / Slurm cluster addons and health.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- Bare Metal
- Clusters
- Kubernetes

#### Properties

- [Documentation](https://docs.voltagepark.com/on-demand/deploy-gpus)
- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voltage Park SSH Keys API

List, add, and remove organization SSH public keys used to grant secure access to virtual machines and bare-metal rentals at provision time.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- SSH Keys
- Access
- Organization

#### Properties

- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voltage Park Storage API

Create, list, resize, configure NFS squash on, and terminate shared storage volumes attachable to bare-metal rentals, with an hourly storage rate endpoint.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- Storage
- Volumes
- NFS

#### Properties

- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voltage Park Locations & HostNodes API

Discover available locations, host nodes, and instant-deploy presets with their available GPU resources to inform VM and bare-metal placement.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- Locations
- HostNodes
- Inventory

#### Properties

- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voltage Park Billing API

Retrieve the current combined hourly rate for active rentals and pull historical and monthly organization billing transaction logs.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- Billing
- Usage
- FinOps

#### Properties

- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voltage Park Organization API

Read and update organization details, billing notification settings, and the organization address used for invoicing.

- **Human URL:** [https://docs.voltagepark.com/on-demand/api](https://docs.voltagepark.com/on-demand/api)
- **Base URL:** `https://cloud-api.voltagepark.com/api/v1`

#### Tags

- Organization
- Account
- Management

#### Properties

- [API Reference](https://docs.voltagepark.com/on-demand/api)
- [OpenAPI](openapi/voltage-park-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/voltage-park.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voltage-park.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/voltage-park)
- [Website](https://www.voltagepark.com)
- [Documentation](https://docs.voltagepark.com)
- [Plans](plans/voltage-park-plans-pricing.yml)
- [Rate Limits](rate-limits/voltage-park-rate-limits.yml)
- [Fin Ops](finops/voltage-park-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
