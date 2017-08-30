# nagiosinstall
cài đặt hệ thống nagios để giám sát các máy remote
- trong hệ thống gồm có 1 máy chạy centos đóng vai trò là monitor một máy chạy ubuntu đóng vai trò là remote
- trên máy centos (monitor): có địa chỉ là 192.168.67.224 cài nagios core , nagios plugin, nrpe,và tạo user admin, 
"nagiosadmin",để truy cập vào giao diện web Nagios
- trê máy ubuntu (remote): có địa chỉ 192.168.70.97 cài nagios plugin, nrpe 
