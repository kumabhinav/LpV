int tid;
#pragma omp parallel section num_threads(3)
{
tid = omp_get_thread_num();
printf(tid);
}
