ADD_SUBDIRECTORY(ai)
ADD_SUBDIRECTORY(cdr)
ADD_SUBDIRECTORY(cgm)
ADD_SUBDIRECTORY(cvg)
ADD_SUBDIRECTORY(drw)
ADD_SUBDIRECTORY(emf)
ADD_SUBDIRECTORY(fh)
ADD_SUBDIRECTORY(idml)
ADD_SUBDIRECTORY(odg)
ADD_SUBDIRECTORY(oodraw)
ADD_SUBDIRECTORY(pages)
ADD_SUBDIRECTORY(pct)
IF(HAVE_POPPLER)
	ADD_SUBDIRECTORY(pdf)
ELSE(HAVE_POPPLER)
	ADD_SUBDIRECTORY(ps)
ENDIF(HAVE_POPPLER)
# ADD_SUBDIRECTORY(pgs)
# ADD_SUBDIRECTORY(ppp)
ADD_SUBDIRECTORY(pm)
ADD_SUBDIRECTORY(pub)
ADD_SUBDIRECTORY(shape)
ADD_SUBDIRECTORY(sml)
ADD_SUBDIRECTORY(svg)
ADD_SUBDIRECTORY(svm)
ADD_SUBDIRECTORY(uniconvertor)
ADD_SUBDIRECTORY(viva)
ADD_SUBDIRECTORY(vsd)
ADD_SUBDIRECTORY(wmf)
ADD_SUBDIRECTORY(wpg)
ADD_SUBDIRECTORY(xar)
ADD_SUBDIRECTORY(xfig)
ADD_SUBDIRECTORY(xps)
