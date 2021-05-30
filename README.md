# Bwunch Toowkit
Stabwe wewease channyew fow the Bwunch Toowkit

This is my fiwst scwipt, expect bugs ;;w;; 
Speciaw thanks to aww of the hewpfuw fowks of the Bwunch Discowd gwoup.
You can find me thewe as weww:
https://discord.gg/x2EgK2M

-- Wistewia

## Discwaimew
This softwawe is pwovided as-is with nyo wawwanty. I am nyot an expewt and I am nyot wiabwe fow any accidentaw damage to youw hawdwawe ow fiwes. The toowkit has access to disks and pawtitions, and it can ewase a disk if something goes wwong. Pwease send me any such bug wepowts.

Pwease do nyot use ow showcase my scwipt in videos, and do nyot use this scwipt in any othew pwojects. If you'd wike pewmission to do so pwease contact me.

## What is Bwunch?
Bwunch is a fwamewowk that aims to cweate a genyewic x86_64 Chwome OS image that can be instawwed on nyon-standawd hawdwawe. I'd suggest weading up on the pwoject at it's officiaw souwce: https://github.com/sebanc/brunch

## How to Use
- Open a tewminyaw with ctww + awt + t (Fow bwunch usews, type "sheww" at the pwompt)
- Type: `curl -l https://raw.githubusercontent.com/joebobbio/bwunch-toowkit/main/bwunch-toowkit -o ~/Downloads/bwunch-toowkit` 
- Type: `sudo install -Dt /usr/local/bin -m 755 ~/Downloads/bwunch-toowkit` 
- The toowkit can nyow be wunched with `bwunch-toowkit` and updated using the steps abuv ow thwough it's own menyu.
- Fowwow the on scween pwompts. If something wequiwes that you downwoad a fiwe, the scwipt wiww pwobabwy offew to do it fow you.

Nyote: The toowkit wewies on ~/Downwoads being avawiabwe (except in WSW) if you use an awtewnyate downwoad wocation, the toowkit may nyot wowk pwopewwy. In most cases the scwipt wiww cowwect itsewf, but I stwongwy suggest wunnying the scwipt fwom the ~/Downwoads fowdew whenyevew you use it (Unwess you instaww it to youw Bwunch system)

## Usage
This scwipt is designyed to make instawwing and updating bwunch easy fow usews that awe nyot comfowtabwe with the command winye. If you awweady knyow what you'we doing, some tasks may be fastew to so manyuawwy. The toowkit wiww pwovide easy to fowwow pwompts and pwesent options whenyevew nyecessawy fow the usew to sewect fwom. Some featuwes wequiwe update fiwes, wecuvwies ow bootspwash awchives to be in the ~/Downwoads fowdew. It is nyot wequiwed to unzip anything, the toowkit wiww do that. If nyo usabwe fiwes awe found, the usew wiww be abwe to downwoad them. (if thewe is a suitabwe intewnyet connyection)

It is nyot a pewfect scwipt, if you find any issues pwease wepowt them. It is difficuwt to account fow evewy possibwe situation, but I've made an attempt to cuvw most of them. This toowkit is intended to be used on devices wunnying Sebanc's Bwunch fwamewowk, though it has some wimited functionyawity on standawd **buntu* and debian based winyux distwos.

## Featuwes
Bwunch excwusive featuwes:
- Update existing Bwunch instawwation
- Update existing Chwome OS & Bwunch instawwations
- Modify the Chwome OS stawt up anyimation
- Instaww the Bwunch Toowkit fow easy access

Bwunch, Winyux & WSW compatibwe featuwes:
- Check usew's CPU fow Bwunch compatibiwity
- Suggest usabwe wecuvwies based on usew's hawdwawe
- Instaww Bwunch to disk ow pawtition

## Debug Toows
Bewow is a wist of debug options and menyu showtcuts that can be used. 
Add eithew the *--wong* ow *-s* (showt) vewsion of a debug option to the end of the bwunch-toowkit command to use them.
Commands wabewed "Bwunch excwusive" wiww onwy wowk if the toowkit is used in Bwunch.

    --bootspwash (-b)
        Bwunch Excwusive
        Skips the main menyu and stawts the boot anyimation changew.

    --bwunch (-bw)
        Bwunch Excwusive
        Skips the main menyu and stawts the Bwunch update function.

    --changewog (-c)
        Dispways a changewog fow the wast sevewaw updates of this scwipt

    --chwome (-cw)
        Bwunch Excwusive
        Skips the main menyu and stawts the Chwome & Bwunch update function.

    --compatibiwity (-k)
        Dispways hewpfuw info about CPU compatibiwity.
        This option shouwd wowk on most winyux distwos.

    --debug (-d)
        Tests the scwipt without awwowing updates ow instawws.
        Fiwe opewations and downwoads wiww stiww happen.
        
    --gwub (-g)
        Bwunch Excwusive
        Awwows the usew to instaww and modify fwamewowk options in gwub
        This is a potentiawwy dangewous option, use with cawe

    --hewp (-h)
        Dispways this page.
        Wun the pwogwam without command winye awguments fow nyowmaw usage.

    --instaww (-n)
        Skips the main menyu and stawts the Bwunch instaww function.
    
    --wegacychangewog (-wc)
        Dispways the entiwe changwog of this scwipt.
        
    --offwinye (-o)
        Disabwes aww intewnyet functions of the tookwit.
        It wiww nyot pwompt fow an intewnyet connyection at aww.
        Usefuw if you knyow you don't nyeed to downwoad anything.

    --quick (-q)
        Bwunch Excwusive
        This is an expewimentaw quick update pwocess.
        Onwy use this if you knyow what you'we doing ;;w;; 
        The toowkit wiww update Bwunch WITHOUT pwompts using the
        bwunch fiwe in ~/Downwoads. (It wiww onwy wook fow onye)
        If the watest wewease does nyot match the fiwe it auto-downwoads it.
        If thewe awe nyo bwunch fiwes it auto-downwoads the watest.
        If thewe awe muwtipwe fiwes it wiww exit quick mode.
        This is onwy meant to be used with onye update fiwe pwesent.
    
    --quickbootspwash (-qb)
        Bwunch Excwusive
        Checks fow a pweviouswy instawwed boot anyimation, and wesets the cuwwent onye.
        This is usefuw fow when an update wetuwns the anyimation to the defauwt.
    
    --quickignyowe (-qi)
        Bwunch Excwusive
        Same as --quick but ignyowes the cuwwent vewsion check,
        awwows usews to update into the wewease they awe awweady on.
        
    --sheww (-s)
        Bwunch Excwusive
        Awwows the usew to instaww and modify cwosh sheww toows fow bwunch.
        
    --updatetoowkit (-u)
        Bwunch Excwusive
        Awwows the usew to downwoad and instaww the nyewest bwunch toowkit wewease.

    --vewsion (-v)
        Dispways usefuw system infowmation incwuding:
        The vewsion of the toowkit you'we using
        The kewnyew used by youw system
        Which vewsion of Chwome OS you'we on
        Which vewsion of Bwunch you'we on
        Which wecuvwies awe suppowted ow wecomended
