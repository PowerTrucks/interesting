#how to sideload onto a mac #(maybe)

#interesting

#perl -pi -e 's/\x03\x00\x85\xC0\x74\x7A\xE8/\x03\x00\x85\xC0\xEB\x7A\xE8/g;' -e 
#'s/\x20\x04\x00\x34\x61\x44\x00\x94/\x20\x04\x00\x35\x61\x44\x00\x94/g'

#&& codesign -f -s - /Applications/App

#codesign --force --deep --sign - /Applications/App/App.a

