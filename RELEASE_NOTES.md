### Version 1.1.8
- Added new endpoint `importer-mappings/` for getting a mapping of importers for file names
- Ran black

### Version 1.1.7
- Add a file name check to void user uploading files with name starting with space
- Update list endpoint so that it only hide .globus_id file by default

### Version 1.1.3
- Add a add-acl-concierge endpoint
- Added configs for that endpoint
- Added options to dockerfile/docker-compose

### Version 1.1.2
- Added capability to check 'kbase_session_backup' cookie
- Added a `add-acl` and `remove-acl` endpoint for globus endpoint access
- Change logging to STDOUT


### Version 1.1.0
- Added a `download` endpoint for files
