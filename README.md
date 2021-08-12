# install_openvpn_server
Install and Configure OpenVPN server

Clone the repo
git clone https://github.com/bakriabbas/install_openvpn_server.git

Navigate to the directory
cd install_openvpn_server

Grant execute permissions
chmod u+x install_ovpn_server.sh
chmod u+x gen_client_config.sh

Run the installation script
./install_ovpn_server
Note: script will generate a client named client1

If you want to add new client run
./gen_client_config.sh client_name
or
./gen_client_config.sh