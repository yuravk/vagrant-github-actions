Vagrant.configure("2") do |config|
    config.vm.box = "almalinux/9"

    config.vm.define 'almalinux'

    # Prevent SharedFoldersEnableSymlinksCreate errors
    config.vm.synced_folder ".", "/vagrant", disabled: true
end