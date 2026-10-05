# repository-entity-store

The fabric's repository side for entities, meant to get, create and change an entity over the iceoryx2 ring.

## What it is for

A repository answers for stored entities. This one shares memory with the ring `transport-ingest-python` opens, so its environment pins the same Python and iceoryx2 as that transport. It holds the environment and the generated entity codec; the service and conformance modules its pixi tasks call are not written.

## Build

    pixi install

## Licence

MIT. See [LICENSE](LICENSE).
