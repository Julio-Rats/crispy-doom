AM_CFLAGS=-I$(top_srcdir)/src                           \
          -I$(top_srcdir)/textscreen                    \
          @SDL_CFLAGS@ @SDLMIXER_CFLAGS@ @SDLNET_CFLAGS@

EXTRA_DIST =                    \
        CMakeLists.txt          \
        strife_icon.c

noinst_LIBRARIES=libstrife.a

libstrife_a_SOURCES =           \
am_map.c           am_map.h     \
deh_ammo.c                      \
deh_cheat.c                     \
deh_strife.c                    \
deh_frame.c                     \
deh_misc.c         deh_misc.h   \
deh_ptr.c                       \
deh_sound.c                     \
deh_thing.c                     \
deh_weapon.c                    \
                   d_englsh.h   \
d_items.c          d_items.h    \
d_main.c           d_main.h     \
d_net.c                         \
                   doomdata.h   \
doomdef.c          doomdef.h    \
doomstat.c         doomstat.h   \
                   d_player.h   \
dstrings.c         dstrings.h   \
                   d_textur.h   \
                   d_think.h    \
f_finale.c         f_finale.h   \
f_wipe.c           f_wipe.h     \
g_game.c           g_game.h     \
hu_lib.c           hu_lib.h     \
hu_stuff.c         hu_stuff.h   \
info.c             info.h       \
m_menu.c           m_menu.h     \
m_crispy.c         m_crispy.h   \
m_random.c         m_random.h   \
m_saves.c          m_saves.h    \
p_ceilng.c                      \
p_dialog.c         p_dialog.h   \
p_doors.c                       \
p_enemy.c                       \
p_floor.c                       \
p_inter.c          p_inter.h    \
p_lights.c                      \
                   p_local.h    \
p_map.c                         \
p_maputl.c                      \
p_mobj.c           p_mobj.h     \
p_plats.c                       \
p_pspr.c           p_pspr.h     \
p_saveg.c          p_saveg.h    \
p_extsaveg.c       p_extsaveg.h \
p_setup.c          p_setup.h    \
p_sight.c                       \
p_spec.c           p_spec.h     \
p_switch.c                      \
p_telept.c                      \
p_tick.c           p_tick.h     \
p_user.c                        \
r_bsp.c            r_bsp.h      \
r_data.c           r_data.h     \
                   r_defs.h     \
r_draw.c           r_draw.h     \
                   r_local.h    \
r_main.c           r_main.h     \
r_plane.c          r_plane.h    \
r_segs.c           r_segs.h     \
r_sky.c            r_sky.h      \
                   r_state.h    \
r_things.c         r_things.h   \
s_sound.c          s_sound.h    \
sounds.c           sounds.h     \
st_lib.c           st_lib.h     \
st_stuff.c         st_stuff.h   \
wi_stuff.c         wi_stuff.h

if HAVE_ICONS

strife_icon.c : $(top_builddir)/data/strife.png
	$(top_builddir)/data/convert-icon $(top_builddir)/data/strife.png $@

endif
