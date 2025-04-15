#!/bin/bash
function typewriter
{    text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter "welcome I am an advanced AI from the future that has the ability to guess the number your thinking of " .1
read -p "please choose a number " guess
sleep 1
clear
sleep 2
function typewriter1
{   text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter1 "Finding Social security number" .1
echo
function typewriter6
{ text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter6 "####################################   (100%)" .1
echo
sleep 1
clear
sleep 2
function typewriter2
{   text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter2 "Scaning vibes." .1
echo
function ProgressBar {
    let _progress=(${1}*100/${2}*100)/100
    let _done=(${_progress}*4)/10
    let _left=40-$_done
    _fill=$(printf "%${_done}s")
    _empty=$(printf "%${_left}s")
printf "\rProgress : [${_fill// /#}${_empty// /-}] ${_progress}%%" 
}
_start=1
_end=100
for number in $(seq ${_start} ${_end})
do
    sleep 0.1
    ProgressBar ${number} ${_end}
done
printf '\nFinished!\n'
sleep 1
clear
sleep 2
function typewriter3
{  text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter3 "Reading Textbooks" .1 
echo
progress()
{ local elapsed=1
  local total=4
  printf -v percent " %s%%" $(( (elapsed * 100) / total ))
  cols=$(tput cols 2>/dev/null || echo 80)
  width=$(( cols-${#percent} ))
  mid=$(( (width * elapsed) / total ))
  printf "\r"
  for (( i=0; i<mid ; i=i+1 )); do printf "▇"; done
  for (( i=mid ; i<width ; i=i+1 )); do printf "░"; done
  echo -n "$percent"
  sleep 1
  local elapsed=2
  local total=4
  printf -v percent " %s%%" $(( (elapsed * 100) / total ))
  cols=$(tput cols 2>/dev/null || echo 80)
  width=$(( cols-${#percent} ))
  mid=$(( (width * elapsed) / total ))
  printf "\r"
  for (( i=0; i<mid ; i=i+1 )); do printf "▇"; done
  for (( i=mid ; i<width ; i=i+1 )); do printf "░"; done
  echo -n "$percent"
  sleep 1
  local elapsed=3
  local total=4
  printf -v percent " %s%%" $(( (elapsed * 100) / total ))
  cols=$(tput cols 2>/dev/null || echo 80)
  width=$(( cols-${#percent} ))
  mid=$(( (width * elapsed) / total ))
  printf "\r"
  for (( i=0; i<mid ; i=i+1 )); do printf "▇"; done
  for (( i=mid ; i<width ; i=i+1 )); do printf "░"; done
  echo -n "$percent"
  sleep 1
  local elapsed=4
  local total=4
  printf -v percent " %s%%" $(( (elapsed * 100) / total ))
  cols=$(tput cols 2>/dev/null || echo 80)
  width=$(( cols-${#percent} ))
  mid=$(( (width * elapsed) / total ))
  printf "\r"
  for (( i=0; i<mid ; i=i+1 )); do printf "▇"; done
  for (( i=mid ; i<width ; i=i+1 )); do printf "░"; done
  echo -n "$percent"=
  }
progress
sleep 1
clear
sleep 2
function typewriter4
{ text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter4 "Creating Guess." .1
echo " "
sp='/-\|'
printf ' '
abc=0
while [ $abc -lt "30" ]; do
    printf '\b%.1s' "$sp"
    sp=${sp#?}${sp%???}
    sleep 0.1
    abc=$(($abc + 1 ))
done
sleep 1
clear
sleep 2
function typewriter5
{  text="$1"
    delay="$2"
    for i in $(seq 0 $(expr length "${text}")) ; do
        echo -n "${text:$i:1}"
        sleep ${delay}
    done }
typewriter5 "Your number is $guess." .1
sleep 4
clear
