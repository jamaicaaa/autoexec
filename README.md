# autoexec
__________________________________________
// LEFT 4 DEAD 2 AUTOEXEC.CFG //
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
__________
// Materials
¯¯¯¯¯¯¯¯¯¯
mat_monitorgamma_tv_enabled "1"       // default 0; increases brightness dramatically
mat_hdr_enabled "0"                    
mat_fastnobump "1" 
mat_bloom_scalefactor_scalar 0	
mat_grain_scale_override 0
cam_ideallag 0
cl_playerspraydisable 0
voice_enable 1
cl_observercrosshair 0
_______
//BINDS
¯¯¯¯¯¯¯	
bind "q" "lastinv"
bind "v" "slot5;cl_viewmodelfovsurvivor 55"
bind 0 "say !ready;cl_viewmodelfovsurvivor 55"
bind 9 "say !unready"
bind 8 "say !pause"
bind 7 "say !tank;say !current"
bind 6 "say !spectate"
bind 5 "say !health"
bind l "say !bonesaw 478;say !bonesaw 493"
bind leftarrow +left
bind rightarrow +right
____________________
// START UP SETTINGS
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
con_enable "1"							
spec_allowroaming "1"																	
cl_showhelp "0"											
cl_forcepreload "1"          								

___________________________________________
// RATE SETTINGS & NET USAGE GRAPH SETTINGS
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
mat_grain_scale_override "0"					// FILM GRAIN AMOUNT
mat_monitorgamma "1.6"						// MONITOR GAMMA MAX BRIGHTNESS
mat_bloom_scalefactor_scalar "0"				// BLOOM SCALE FACTOR	
r_dynamic "0"							// DYNAMIC
r_eyemove "0"							// ENABLES EYE MOVEMENT	
cl_viewmodelfovsurvivor "55"					// VIEW MODEL OF SURVIVOR AND INFECTED
cl_showpos "1"
rate "100000"							// MAX BYTES/SEC TO RECIEVE DATA		(Default 10000)
cl_cmdrate "100"							// NUMBER OF Command PACKETS/SEC TO SEND	(Default 30)
cl_updaterate "100"						// NUMBER OF PACKETS/SEC OF UPDATES TO RECIEVE	(Default 20)
cl_interp "0"						// SETS THE INTERPOLATION AMOUNT SPECIFIED	(Default 0.1)
cl_interp_ratio "0"						// SETS THE INTERPOLATION AMOUNT LIMIT		(Default 2)
cl_lagcompensation "1"						// PERFORM SERVER SIDE LAG COMPENSATION		(Default 1)
cl_resend "1.5"           					// DELAY IN SECONDS BEFORE CLIENT RECONNECTS	(Default 6)
cl_timeout "30"							// SECONDS BEFORE DISCONNECTS FROM SERVER	(Default 120)
net_maxroutable "1200"						// MAX PACKET SIZE BEFORE THEY ARE SLPIT	(Default 1200)
net_graphpos "1"						// NETWORK USAGE GRAPH POSITION			(Default 1)
net_graphproportionalfont "0"					// NETWORK USAGE GRAPH PROPORTIONAL FONT	(Default 1)
budget_show_history "0"            				// SHOW HISTORY NETWORK USAGE GRAPH		(Default 1)
func_break_max_pieces "0"
cl_lagcomp_errorcheck "0"
cl_predictweapons "1"
cl_smooth "0"
cl_smoothtime "0.01"
fps_max_override "0"
net_scale 100000000000
net_graphheight 0
net_graph 5
net_graphmsecs 0
net_graphshowinterp 0
net_graphshowlatency 0
net_graphsolid 0
_____________________________
// MOUSE & CROSSHAIR SETTINGS
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
sensitivity "2.5"							// MOUSE SENSITIVITY				(Default 3)
m_rawinput "1"							// USE RAW INPUT FOR MOUSE INPUT		(Default 0)
m_mousespeed "0"						// USE WINDOWS MOUSE ACCELERATION		(Default 1)
cl_colorblind "0"						// SHOW COLOR BLIND CROSHSAIR			(Default 0)
cl_crosshair_dynamic "0"					// CROSSHAIR SCALES BASED ON ACCURACY		(Default 1)
cl_crosshair_thickness "4.9"					// CROSSHAIR THICKNESS IN PIXELS		(Default 2)
cl_crosshair_blue "0"						// CROSSHAIR BLUE				(Default 220)
cl_crosshair_red "255"						// CROSSHAIR RED				(Default 138)
cl_crosshair_green "0"			  		        // CROSSHAIR GREEN				(Default 182)
closecaption "1"						// ENABLES CLOSE CAPTIONING			(Default 0)
cc_predisplay_time "0"						// CLOSE CAPTION DELAY BEFORE SHOWING CAPTION	(Default 0.25)
cc_linger_time "0.75"						// CLOSE CAPTION LINGER TIME	
muzzleflash_light "0"
r_eyesize "0"
r_eyeshift_z "0"
r_eyeshift_y "0"
r_eyeshift_x "0"
r_PhysPropStaticLighting "0"
cl_ragdoll_limit "0"
______________________
// GLOW COLOR SETTINGS
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
cl_glow_ghost_infected_r "1.00"					// COLOR OF INFECTED GHOST 			WHITE
cl_glow_ghost_infected_g "1.00"					// Only Survivor View
cl_glow_ghost_infected_b "1.00"					// -
cl_glow_infected_r "0.00"					// COLOR OF INFECTED TEAM MATE			BLUE
cl_glow_infected_g "0.25"					// Only Infected View
cl_glow_infected_b "1.00"					// -
cl_glow_survivor_r "0.00"					// COLOR OF SURVIVOR TEAM MATE			BLUE
cl_glow_survivor_g "0.25"					// Only Survivor View
cl_glow_survivor_b "1.00"					// -
cl_glow_survivor_health_high_r "0.00" 				// COLOR OF SURVIVORS WITH HIGH HEALTH		GREEN
cl_glow_survivor_health_high_g "1.00"				// Only Infected View
cl_glow_survivor_health_high_b "0.00"				// -
cl_glow_survivor_health_med_r "1.00"				// COLOR OF SURVIVORS WITH MEDIUM HEALTH	YELLOW
cl_glow_survivor_health_med_g "0.75"				// Only Infected View
cl_glow_survivor_health_med_b "0.00"				// -
cl_glow_survivor_health_low_r "1.00"				// COLOR OF SURVIVORS WITH LOW HEALTH		ORANGE
cl_glow_survivor_health_low_g "0.25"				// Only Infected View
cl_glow_survivor_health_low_b "0.00"				// -
cl_glow_survivor_health_crit_r "1.00"				// COLOR OF SURVIVOR WHEN INCAPACITATED		RED
cl_glow_survivor_health_crit_g "0.00"				// Only Infected View
cl_glow_survivor_health_crit_b "0.00"				// -
cl_glow_survivor_hurt_r "1.00"					// COLOR OF SURVIVOR WHEN INCAPACITATED		RED
cl_glow_survivor_hurt_g	"0.00"					// Only Survivor View
cl_glow_survivor_hurt_b	"0.00"					// -
cl_glow_survivor_vomit_r "0.50"					// COLOR OF SURVIVORS WHEN PUKED		PURPLE
cl_glow_survivor_vomit_g "0.00"					// Only Infected View
cl_glow_survivor_vomit_b "1.00"					// -
cl_glow_infected_vomit_r "0.50"					// COLOR OF SURVIVORS WHEN PUKED		PURPLE
cl_glow_infected_vomit_g "0.00"					// Only Infected View
cl_glow_infected_vomit_b "1.00"					// -
cl_glow_item_r "1.00"						// COLOR OF ITEMS IN RANGE 			ORANGE
cl_glow_item_g "0.25"						// Both Survivor & Infected View
cl_glow_item_b "0.00"						// -
cl_glow_item_far_r "1.00"					// COLOR OF ITEMS OUT OF RANGE 			ORANGE
cl_glow_item_far_g "0.25"					// Both Survivor & Infected View
cl_glow_item_far_b "0.00"					// -
cl_glow_thirdstrike_item_r "1.00"				// COLOR OF ITEMS WHILE BLACK & WHITE 		ORANGE
cl_glow_thirdstrike_item_g "0.25"				// Only Survivor View
cl_glow_thirdstrike_item_b "0.00"				// -

//FPS CVARS

mat_queue_priority "2"; //# (Def.1) TO USE IF YOU GOT LAGS/ LOW FPS
cl_detail_max_sway "0"; //# (Def.5) Amplitude of the detail prop sway
cl_forcepreload "0"; //# (def.0) Preload map and models to ram
cl_ragdoll_limit "0"; //# (def.20)Dead infected are removed more quickly *
dsp_slow_cpu "1"; //# (def.0) Reduces the quality of dsp sound effects
func_break_max_pieces "0"; //# (def.15)Reduces gibs
r_cheapwaterend "1"; //# (def.0) worse water rendering
r_cheapwaterstart "1"; //# (def.0) worse water rendering
r_drawmodelstatsoverlaymin "0.1"; //# (Def.0) time in milliseconds that a model must take to render before showing an overlay in r_drawmodelstatsoverlay 2
r_drawmodelstatsoverlaymax "1.5"; //# (Def.1) time in milliseconds beyond which a model overlay is fully red in r_drawmodelstatsoverlay 2
r_dynamic "0"; //# (def.1) Disables dynamic shadows
r_PhysPropStaticLighting "0"; //# (def.0) Faster lighting on phys objects
r_skyboxfogfactor "0.0"; //# Lerp between 2D skybox rendering and fog color. 0.0 means regular 2D skybox rendering, 1.0 is fully fog color.
