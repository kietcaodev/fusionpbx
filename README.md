Change logo basebs

cd /tmp
git clone https://github.com/kietcaodev/fusionpbx.git logo_basebs
cd logo_basebs
rm -rf /var/www/fusionpbx/themes/default/images
rm -rf /var/www/fusionpbx/themes/default/favicon.ico
cp -r /tmp/logo_basebs/* /var/www/fusionpbx/themes/default/
