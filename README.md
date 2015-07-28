# xml2yaml

Perl script to convert xml to yaml

## Use
You need the perl modules YAML::Syck and XML::Simple installed. This can be performed like that:

	cpanp i YAML::Syck
	cpanp i XML::Simple

Then clone the script from github:

	git clone https://github.com/Gioyik/xmlPLyaml

Now run the script:

	perl xmlPLyaml.pl file.xml > file.yaml
