#!/usr/bin/sh

echo -n "Enter marks in 3 subjects:  "
read m1 m2 m3 

tot=$(expr  $m1 +  $m2 +  $m3 )
echo   "Total:   $tot"

per=$(expr  $tot  /   3)
echo   "percentage:   $per"


if  [ [   $per -ge 100   ] ];   then
	echo   "S   Grade"
elif   [ [   $per -ge 90   ] ];   then
        echo   "A   Grade"
elif   [ [   $per -ge 80   ] ];   then
        echo   "B  Grade"
elif   [ [  $per -ge 70  ] ];   then
        echo   "c   Grade"
else
     echo "Fail"
fi     
