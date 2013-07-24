
404pnf: original found at: http://www.technetra.com/2008/11/11/codemagic-renamerb-a-ruby-version-of-perls-rename-command/

404pnf: an one-liner: http://www.psteiner.com/2012/05/how-to-rename-files-with-ruby.html

    ruby -e 'Dir.glob("IP*.xml").each { |f| File.rename(f,f[24..-1]) }'

