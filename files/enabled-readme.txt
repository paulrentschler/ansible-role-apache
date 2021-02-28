#
# This directory holds the enabled Apache 2.x virtual host configuration
# files; any files in this directory will be processed as part of the Apache
# configuration.
#
# All files in this directory should be symlinks to the original files
# created in the ../sites-available directory. To disable a virtual host,
# delete the symlink.
#
# To enable a site:
#   sudo a2ensite 000-site.domain.tld
#
# To disable a site:
#   sudo a2dissite 000-site.domain.tld
#
#
# Files are processed in alphabetical/numerical order, so each virtual
# host configuration file should start with a three digit number. The
# first digit should be used to indicate different domains, the second
# digit should indicate different hosts within the domain, and the third
# digit should be used to indicate different configurations. The filename
# should also include the host and domain of the server and be suffixed
# with "-ssl" if the configuration is for an SSL virtual host.
#
