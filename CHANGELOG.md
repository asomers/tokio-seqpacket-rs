v0.3.0:
  * Update to tokio 0.3.2.
  * Remove `get_peer_cred` since we can't create `UCred` structs anymore.

v0.2.1:
  * Fix receiving of ancillary data.

v0.2.0:
  * Add supported for vectored I/O.
  * Add support for ancillary data.
  * Allow sockets to be split in a read half and a write half.
