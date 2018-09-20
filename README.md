Specs
=====

Use these Specs to add Ensembles 2.x to your project.

1. If you don't already have access to the Ensembles 2.x Git repo, request access by emailing [support@mentalfaculty.com](mailto:support@mentalfaculty.com).
2. Add The Mental Faculty private repo to your Cocoapods installation.
    
        pod repo add mentalfaculty https://github.com/mentalfaculty/Specs.git

3. Include Ensembles in your Podfile.

        source 'https://github.com/mentalfaculty/Specs.git'
        source 'https://github.com/CocoaPods/Specs.git'

        platform :ios, '7.0'
        pod "Ensembles", "~> 2.0"
