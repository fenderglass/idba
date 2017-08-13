AM_LDFLAGS = -fopenmp -pthread
LIBS = $(top_srcdir)/lib/libassembly.a @LIBS@
AM_CXXFLAGS = -Wall -O3 -fopenmp -pthread
INCLUDES =  -I$(top_srcdir)/src -I$(top_srcdir)/gtest_src 

idba_tran_test_SOURCES = $(top_srcdir)/src/tools/idba_tran_test.cpp
validate_component_SOURCES = $(top_srcdir)/src/tools/validate_component.cpp
print_graph_SOURCES = $(top_srcdir)/src/tools/print_graph.cpp
scaffold_SOURCES = $(top_srcdir)/src/tools/scaffold.cpp
split_fq_SOURCES = $(top_srcdir)/src/tools/split_fq.cpp
test_SOURCES = $(top_srcdir)/src/tools/test.cpp
filter_blat_SOURCES = $(top_srcdir)/src/tools/filter_blat.cpp
validate_reads_blat_SOURCES = $(top_srcdir)/src/tools/validate_reads_blat.cpp
sample_reads_SOURCES = $(top_srcdir)/src/tools/sample_reads.cpp
fa2fq_SOURCES = $(top_srcdir)/src/tools/fa2fq.cpp
validate_rna_SOURCES = $(top_srcdir)/src/tools/validate_rna.cpp
sort_psl_SOURCES = $(top_srcdir)/src/tools/sort_psl.cpp
validate_contigs_mummer_SOURCES = $(top_srcdir)/src/tools/validate_contigs_mummer.cpp
parallel_rna_blat_SOURCES = $(top_srcdir)/src/tools/parallel_rna_blat.cpp
filter_contigs_SOURCES = $(top_srcdir)/src/tools/filter_contigs.cpp
split_fa_SOURCES = $(top_srcdir)/src/tools/split_fa.cpp
sort_reads_SOURCES = $(top_srcdir)/src/tools/sort_reads.cpp
shuffle_reads_SOURCES = $(top_srcdir)/src/tools/shuffle_reads.cpp 

filterfa_SOURCES = $(top_srcdir)/src/release/filterfa.cpp
idba_hybrid_SOURCES = $(top_srcdir)/src/release/idba_hybrid.cpp
idba_subasm_SOURCES = $(top_srcdir)/src/release/idba_subasm.cpp
sim_reads_tran_SOURCES = $(top_srcdir)/src/release/sim_reads_tran.cpp
idba_SOURCES = $(top_srcdir)/src/release/idba.cpp
parallel_blat_SOURCES = $(top_srcdir)/src/release/parallel_blat.cpp
idba_tran_SOURCES = $(top_srcdir)/src/release/idba_tran.cpp
split_scaffold_SOURCES = $(top_srcdir)/src/release/split_scaffold.cpp
sim_reads_SOURCES = $(top_srcdir)/src/release/sim_reads.cpp
fq2fa_SOURCES = $(top_srcdir)/src/release/fq2fa.cpp
validate_contigs_blat_SOURCES = $(top_srcdir)/src/release/validate_contigs_blat.cpp
raw_n50_SOURCES = $(top_srcdir)/src/release/raw_n50.cpp
idba_ud_SOURCES = $(top_srcdir)/src/release/idba_ud.cpp 

bin_PROGRAMS = \
	idba_hybrid 

noinst_PROGRAMS = \
	idba_tran_test \
	validate_component \
	print_graph \
	scaffold \
	split_fq \
	test \
	filter_blat \
	validate_reads_blat \
	sample_reads \
	fa2fq \
	validate_rna \
	sort_psl \
	validate_contigs_mummer \
	parallel_rna_blat \
	filter_contigs \
	split_fa \
	sort_reads \
	shuffle_reads \
	filterfa \
	idba_subasm \
	sim_reads_tran \
	idba \
	parallel_blat \
	idba_tran \
	split_scaffold \
	sim_reads \
	fq2fa \
	validate_contigs_blat \
	raw_n50 \
	idba_ud 


