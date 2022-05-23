transition digunakan untuk mengubah nilai dari property html secara halus atau membuat animasi

perbedaan transition dan animation:

transition hanya ada kondisi awal dan akhir
animation ada beberapa kondisi awal keyframe dan akhir

di transition terdapat 4 buah parameter:
[property] <durasi> [fungsi] [delay]

durasi: s/ms

property yang support menggunakan transition:
background-color, background-position, background-size, border, color, filter, font-size, line-height
top, left, bottom, right, margin, padding, width, height, opacity, transform, word-spacing,
letter-spacing, another

transition timing function/fungsi, ada beberapa jenis:
ease(default)
ease-in
ease-out
ease-in-out
linear
cubic-bezier(w,x,y,z)
