This is a readme file for variable expansion

*0x03. Shell, init files, variables and expansions*

The following are the second line of your scripts after the shebang..
Be sure to be in the right directory.. 
And don't forget to RTFM

0. alias ls="rm *"
1. echo "hello "$USER
2. PATH=PATH:/action
3. echo $PATH | tr ':' '\n' | wc -l
4. printenv
5. set
6. BEST="School"
7. export School="BEST"
8. echo $((TRUEKNOWLEDGE + 128))
9. echo $((POWER / DIVIDE)) 
10. echo $((BREATH ** LOVE))
11. echo "$((2#$BINARY))"

12. echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"

13. printf "%.2f\n" $NUM

14. printf '%x\n' $DECIMAL

15. tr 'A-Za-z' 'N-ZA-Mn-za-m'

16. paste - - | cut -d$'\t' -f1

17. printf '%\n' $(( $((5#$(echo $STIR | tr 'stir.' '01234'))) + $((5$#(echo $WATER | tr 'water' '01234'))) )) | tr '01234567' 'bestchol'


Note this is the last task for now under system engineering-devops.... 
Started reading up on C programming cause that's what's next ..
