OBJS                                   += ppc/fmtconvert_altivec.o      \

OBJS-$(CONFIG_AUDIODSP)                += ppc/audiodsp.o
OBJS-$(CONFIG_BLOCKDSP)                += ppc/blockdsp.o
OBJS-$(CONFIG_DSPUTIL)                 += ppc/dsputil_ppc.o
OBJS-$(CONFIG_FFT)                     += ppc/fft_altivec.o
OBJS-$(CONFIG_H264CHROMA)              += ppc/h264chroma_init.o
OBJS-$(CONFIG_H264DSP)                 += ppc/h264dsp.o ppc/hpeldsp_altivec.o
OBJS-$(CONFIG_H264QPEL)                += ppc/h264qpel.o
OBJS-$(CONFIG_HPELDSP)                 += ppc/hpeldsp_altivec.o
OBJS-$(CONFIG_HUFFYUVDSP)              += ppc/huffyuvdsp_altivec.o
OBJS-$(CONFIG_IDCTDSP)                 += ppc/idctdsp.o
OBJS-$(CONFIG_MPEGAUDIODSP)            += ppc/mpegaudiodsp_altivec.o
OBJS-$(CONFIG_MPEGVIDEO)               += ppc/mpegvideo_altivec.o      \
                                          ppc/mpegvideodsp.o
OBJS-$(CONFIG_VIDEODSP)                += ppc/videodsp_ppc.o
OBJS-$(CONFIG_VP3DSP)                  += ppc/vp3dsp_altivec.o

OBJS-$(CONFIG_LLAUDDSP)                += ppc/lossless_audiodsp_altivec.o
OBJS-$(CONFIG_SVQ1_ENCODER)            += ppc/svq1enc_altivec.o
OBJS-$(CONFIG_VC1_DECODER)             += ppc/vc1dsp_altivec.o
OBJS-$(CONFIG_VORBIS_DECODER)          += ppc/vorbisdsp_altivec.o
OBJS-$(CONFIG_VP7_DECODER)             += ppc/vp8dsp_altivec.o
OBJS-$(CONFIG_VP8_DECODER)             += ppc/vp8dsp_altivec.o

ALTIVEC-OBJS-$(CONFIG_DSPUTIL)         += ppc/dsputil_altivec.o         \
                                          ppc/fdct_altivec.o            \

FFT-OBJS-$(HAVE_GNU_AS)                += ppc/fft_altivec_s.o
FFT-OBJS-$(HAVE_VSX)                   += ppc/fft_vsx.o
ALTIVEC-OBJS-$(CONFIG_FFT)             += $(FFT-OBJS-yes)
