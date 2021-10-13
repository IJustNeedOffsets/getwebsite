echo "getwebsite"
if [ $1 == ]
 then
     echo "please type getwebsite /WEBSITE/URL/"
     echo ""
else
wget --recursive --page-requisites --adjust-extension --span-hosts --convert-links --restrict-file-names=windows --domains $1 --no-parent $1
echo "website has been downloaded"
fi
