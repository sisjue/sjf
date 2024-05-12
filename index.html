import argparse

parser = argparse.ArgumentParser(description='Process some integers.')
parser.add_argument('--run', type=int, default=1)
args = parser.parse_args()

class Process:
    def __init__(self, pid, arrival_time, burst_time):
        self.pid = pid
        self.arrival_time = arrival_time
        self.burst_time = burst_time

class SJF:
    def SJF_Scheduling(self, processes):
        # 按照到达时间排序
        processes.sort(key=lambda x: x.arrival_time)

        completion_time = 0
        waiting_time = 0
        cycling_time = 0
        num_processes = len(processes)

        while processes:
            # 选择到达时间最短的作业
            next_process = min(processes, key=lambda x: x.burst_time)
            processes.remove(next_process)

            # 计算完成时间和周转时间
            completion_time = max(completion_time, next_process.arrival_time) + next_process.burst_time
            cycling_time = completion_time - next_process.arrival_time

            # 计算等待时间
            waiting_time += max(0, completion_time - next_process.arrival_time - next_process.burst_time)

            print(f"PID: {next_process.pid}, Completion Time: {completion_time}, Cycling Time: {cycling_time}")

        avg_waiting_time = waiting_time / num_processes
        return avg_waiting_time

    def InputFromOutside(self, n):
        processes = []
        for i in range(n):
            print(f"Process {i+1}")
            arrival_time = int(input("Input Arrival Time: "))
            burst_time = int(input("Input Burst Time: "))
            p = Process(i+1, arrival_time, burst_time)
            processes.append(p)
        avg_waiting_time = self.SJF_Scheduling(processes)
        print("Process list generated.")
        return avg_waiting_time

if __name__ == '__main__':
    sjf = SJF()
    if args.run == 1:
        processes = [Process(1, 0, 10), Process(2, 6, 20), Process(3, 8, 30), Process(4, 9, 5), Process(5, 15, 15)]
        avg_waiting_time = sjf.SJF_Scheduling(processes)
        print(f"Average Waiting Time: {avg_waiting_time}")
    elif args.run == 2:
        pro_num = int(input("Input Process num: "))
        avg_waiting_time = sjf.InputFromOutside(pro_num)
        print(f"Average Waiting Time: {avg_waiting_time}")
