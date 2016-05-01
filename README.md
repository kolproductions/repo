# repo
# GitHub Repos
	url = https://kolproductions@github.com/kolproductions/repo.git
	url = git@github.com:kolproductions/repo.git

# Local
 via HTTPS                                                                                         
· git clone https://user@host/git/testing.git
 
 via SSH                                                                                                        
· git clone git@host:repositories/gitolite-admin.git                                                           
· git clone git@host:repositories/linux.git                                               
 
 
       ·   ssh://[user@]host.xz[:port]/path/to/repo.git/

       ·   git://host.xz[:port]/path/to/repo.git/

       ·   http[s]://host.xz[:port]/path/to/repo.git/

       ·   ftp[s]://host.xz[:port]/path/to/repo.git/

       ·   rsync://host.xz/path/to/repo.git/

       An alternative scp-like syntax may also be used with the ssh protocol:

       ·   [user@]host.xz:path/to/repo.git/

       The ssh and git protocols additionally support ~username expansion:

       ·   ssh://[user@]host.xz[:port]/~[user]/path/to/repo.git/

       ·   git://host.xz[:port]/~[user]/path/to/repo.git/

       ·   [user@]host.xz:/~[user]/path/to/repo.git/

       For local respositories, also supported by git natively, the following syntaxes may be used:

       ·   /path/to/repo.git/

       ·    file:///path/to/repo.git/

 # Repository Not Exported Error 
 touch git-daemon-export-ok into proper repo.git directory,  should resolve that problem.
