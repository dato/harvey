load('//sys/src/FLAGS', "LIB_COMPILER_FLAGS")

cc_library(
	name = "libmp",
        copts = LIB_COMPILER_FLAGS,
        includes=[
            "//sys/include",
            "//amd64/include",
        ],
	srcs = [
		"port/betomp.c",
		"port/crt.c",
		"port/crttest.c",
		"port/letomp.c",
		"port/mpadd.c",
		"port/mpaux.c",
		"port/mpcmp.c",
		"port/mpdigdiv.c",
		"port/mpdiv.c",
		"port/mpeuclid.c",
		"port/mpexp.c",
		"port/mpextendedgcd.c",
		"port/mpfactorial.c",
		"port/mpfmt.c",
		"port/mpinvert.c",
		"port/mpleft.c",
		"port/mpmod.c",
		"port/mpmul.c",
		"port/mprand.c",
		"port/mpright.c",
		"port/mpsub.c",
		"port/mptobe.c",
		"port/mptoi.c",
		"port/mptole.c",
		"port/mptoui.c",
		"port/mptouv.c",
		"port/mptov.c",
		"port/mpvecadd.c",
		"port/mpveccmp.c",
		"port/mpvecdigmuladd.c",
		"port/mpvecsub.c",
		"port/strtomp.c"
	]
)
