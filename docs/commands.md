Metamorf can be executed:

        metamorf [command] [optional arguments]


## help
It shows all the commands available and some details.

## manifest
It generates a Manifest Json File with all the information from the data models of the current owner.

## api
It deploys an API that serve all the metadata information. Alpha Version, under development.

## validate
It validates the configuration file.

## init
Metamorf Initialization on the current directory. Optional arguments [-d, --database, -m, --metadata]

## deploy
It deploys on the metadata database all the requirements.

## deploy-example
It deploys on the metadata database all the requirement with metadata information and example data on the data database an example.

## download
It downloads the Metadata Entry of the Owner selected on CSV files, on the directory [entry]. Optional arguments [-s, --select, -o, --owner]

## upload
It uploads the Metadata Entry on the Metadata Database. Optional arguments [-s, --select]

## commit
It commits the actual metadata from your owner.

## recover
It recovers the last commit metadata of your owner. Optional arguments [-s, --select]

## process
It processes all the metadata entry to promote the metadata.

## run
It executes all the sql models. Optional arguments [-s, --select]

## output
It generates the files of the processes on the output directory. Optional arguments [-s, --select]

## delete
It deletes all the metadata from the owner.

## backup
It downloads all the Metadata onto CSV Files to backup all the system. It allows you to recover them in the future using the restore command on an emergency or migration case.

## restore
It restores all the metadata from the backup folder of the repository.

## files
It uploads all the files that are indicated on the metadata.

## metadata
It validates the metadata entry.
