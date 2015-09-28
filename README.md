# First
seq = ("AAGGTTCC")

puts seq

def rev_comp(string)
	string.gsub(/[AGCT]/, 'A' => 'C', 'C' => 'A', 'G' => 'T', 'T' => 'G')
end

puts rev_comp(seq)
puts rev_comp('AAACCCGGGTTT')
