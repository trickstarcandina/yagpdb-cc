{{/*Code by TrickStar

Trigger/Command suggest : -cfs 

This command used to check the content before posting.
I upload a message through a channel and then the right holders will moderate and post it on the main cfs channel
*/}}
{{$note := dbGet 999 "cfs"}}
{{$no := add $note.Value 1}}
{{dbSet 999 "cfs" $no}}
{{ $timezone := "Asia/Ho_Chi_Minh" }} {{/* Edit this */}}
{{ $now := currentTime.In (newDate 0 0 0 0 0 0 $timezone).Location }}
{{ $time := $now.Format "3:04:05 PM" }}
{{ $date := $now.Format "Monday, January 2, 2006" }}
{{$args := parseArgs 0 "Lỗi rùi gõ : -cfs <nội dung>"
    (carg "string" "nội dung")}}
{{if .Message.Attachments}}
    {{range .Message.Attachments}}
    	{{$msgEmbed := cembed
		"title" (joinStr "" "🦅 🦅 🦅      ꧁༺ Peculiar Academy Confession #" (toString (toInt $no)) " ༻ ꧂      🦅 🦅 🦅" ) {{/* Edit this */}}
		"description" (printf "-------------------------------------------------------\n*%s*" ($args.Get 0))
        	"image" (sdict "url" .ProxyURL)  
        	"color" 16763904
		"footer" (sdict "text" (joinStr " " "Confession at" $time $date) "icon_url" "https://cdn.discordapp.com/attachments/829733340155740182/835762811153940490/unknown.png") {{/* Edit this */}} 
    		}}
    	{{$x := sendMessageRetID 835795727421931530 $msgEmbed}} {{/* Edit this. This is channel moderation */}}
    	{{addMessageReactions 835795727421931530 $x "👍"}}
    {{end}}
{{else}}
    {{$msgEmbed := cembed
		"title"  (joinStr "" "🦅 🦅 🦅      ꧁༺ Peculiar Academy Confession #" (toString (toInt $no)) " ༻ ꧂      🦅 🦅 🦅" ) {{/* Edit this */}}
		"description" (printf "-------------------------------------------------------\n*%s*\n-------------------------------------------------------\n" ($args.Get 0))
        	"color" 16763904
		"footer" (sdict "text" (joinStr " " "Confession at" $time $date) "icon_url" "https://cdn.discordapp.com/attachments/829733340155740182/835762811153940490/unknown.png") {{/* Edit this */}}
    		}}
    	{{$x := sendMessageRetID 835795727421931530 $msgEmbed}} {{/* Edit this. This is channel moderation */}}
    	{{addMessageReactions 835795727421931530 $x "👍"}}
{{end}}
{{deleteTrigger 1}}
