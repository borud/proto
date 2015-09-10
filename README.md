# My default Maven archetype

This is just a default Maven archetype I use that has a few useful
dependencies.  Use at your own risk.  The maven repository where this archetype
resides is:  `https://raw.githubusercontent.com/borud/repository/mvn-repo/`

# Usage

    mvn archetype:generate \
    	-DarchetypeRepository=https://raw.githubusercontent.com/borud/repository/mvn-repo/ \
        -DarchetypeGroupId=org.borud   \
        -DarchetypeArtifactId=proto    \
        -DarchetypeVersion=1.1
    
# References

  - http://stackoverflow.com/questions/14013644/hosting-a-maven-repository-on-github
